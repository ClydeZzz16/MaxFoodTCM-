## **TC-UI-04:** Offline Screen Display Indicators  

> **Summary:** Offline Screen Display Indicators verification.  <br>

**Preconditions:** App is running normally.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Toggle device cellular data and WiFi settings off. | Verify the app displays a full-screen offline warning overlay indicating lack of connection. |
 |  2 | Toggle internet connection back on.                | Verify the overlay dismisses and the home screen reloads cached items. |  

**Post-conditions:**  

 - Offline overlay displays correctly, restricting interface operations gracefully.  
