## **TC-AUTH-05:** Logout Session Destruction  

> **Summary:** Logout Session Destruction verification.  <br>

**Preconditions:** User is currently logged in with an active session.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the Profile screen.                    | Verify that profile configuration screen is shown. |
 |  2 | Scroll down and tap the 'Logout' button.           | Verify that the loading indicator is displayed, the Supabase session is revoked, and the user is redirected to the landing page. |
 |  3 | Attempt to navigate back to dashboard.             | Verify that navigating back is blocked and redirects to the landing page. |  

**Post-conditions:**  

 - Auth session destroyed on client and server; local profile state cache is invalidated.  
