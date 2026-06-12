## **AUTH-005:** User Signup Password Mismatch  

> **Summary:** User Signup Password Mismatch verification.  <br>

**Preconditions:** User is on the signup page.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Enter valid email, a password, and a mismatched confirm password. | Verify text fields display input.                  |
 |  2 | Tap 'Sign Up' button.                              | Verify action is blocked and a warning toast indicates that passwords do not match. |  

**Post-conditions:**  

 - Signup registration is blocked; no request sent to server.  
