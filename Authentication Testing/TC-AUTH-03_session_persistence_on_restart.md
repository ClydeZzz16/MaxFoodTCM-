## **TC-AUTH-03:** Session Persistence On Restart  

> **Summary:** Session Persistence On Restart verification.  <br>

**Preconditions:** User is signed in and has a valid active session.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Close the UbayHarvest application completely (kill process). | Verify the application process is terminated.      |
 |  2 | Relaunch the UbayHarvest application.              | Verify the splash screen loads, checks local session storage, and routes directly to the home dashboard screen without prompting for sign-in. |  

**Post-conditions:**  

 - Session remains active and user is on the authenticated dashboard.  
