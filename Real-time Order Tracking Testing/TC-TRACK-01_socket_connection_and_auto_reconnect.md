## **TC-TRACK-01:** Socket Connection And Auto Reconnect  

> **Summary:** Socket Connection And Auto Reconnect verification.  <br>

**Preconditions:** User has placed an order that is ready for tracking.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the Order Tracking page.               | Verify tracking map or progress timeline renders, establishing a live connection. |
 |  2 | Disconnect internet connection temporarily.        | Verify that 'Connection Lost' indicator displays and map status freezes. |
 |  3 | Re-enable internet connection.                     | Verify that socket automatically reconnects, syncs status, and indicator disappears. |  

**Post-conditions:**  

 - Real-time tracking handles connection dropouts and auto-reconnects safely.  
