## **TC-ALRT-03:** Custom Toast Notification Overlay On Home  

> **Summary:** Custom Toast Notification Overlay On Home verification.  <br>

**Preconditions:** User is currently on the dashboard home screen.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Simulate an incoming alert notification (e.g. a matching listing is added). | Verify a custom sliding toast notification overlay appears at the top of the home screen showing alert details. |
 |  2 | Wait 5 seconds.                                    | Verify toast automatically slides out of view smoothly. |  

**Post-conditions:**  

 - Real-time sliding toast overlay renders correctly for alerts/notifications.  
