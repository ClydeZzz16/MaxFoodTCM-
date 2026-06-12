## **AUTH-001:** User Login Valid Credentials  

> **Summary:** User Login Valid Credentials verification.  <br>

**Preconditions:** User has a registered active account with email and password.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Launch application and enter valid registered email and password in login form. | Verify input fields accept characters correctly.   |
 |  2 | Tap the 'Sign In' button.                          | Verify progress spinner displays and screen redirects to home dashboard. |
 |  3 | Inspect dashboard user state.                      | Verify authenticated header displays user profile name. |  

**Post-conditions:**  

 - Session is created in Supabase Auth and cached locally.  
