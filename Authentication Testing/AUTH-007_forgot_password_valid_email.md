## **AUTH-007:** Forgot Password Valid Email  

> **Summary:** Forgot Password Valid Email verification.  <br>

**Preconditions:** User is on forgot password page.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Enter a valid registered email address.            | Verify field displays input.                       |
 |  2 | Tap 'Reset Password' button.                       | Verify a success snackbar displays and a recovery link is sent to user email. |  

**Post-conditions:**  

 - Password recovery request is registered on Supabase, and recovery email is dispatched.  
