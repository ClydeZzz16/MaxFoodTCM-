## **AUTH-009:** Logout Valid Session  

> **Summary:** Logout Valid Session verification.  <br>

**Preconditions:** User has an active authenticated session.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Open Profile settings page.                        | Verify profile details load.                       |
 |  2 | Tap 'Logout' button.                               | Verify loading state, local cache invalidation, and redirection to landing page. |  

**Post-conditions:**  

 - Auth session destroyed on client and server; protected route access restricted.  
