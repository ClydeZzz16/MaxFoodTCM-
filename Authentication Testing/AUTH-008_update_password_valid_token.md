## **AUTH-008:** Update Password Valid Token  

> **Summary:** Update Password Valid Token verification.  <br>

**Preconditions:** User has clicked forgot password email recovery deep link.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Enter a new password in the password reset input form. | Verify input is accepted.                          |
 |  2 | Tap 'Save Password' button.                        | Verify session token resolves, password updates on server, and app redirects to dashboard. |  

**Post-conditions:**  

 - Password is changed in auth schema, establishing active authenticated session.  
