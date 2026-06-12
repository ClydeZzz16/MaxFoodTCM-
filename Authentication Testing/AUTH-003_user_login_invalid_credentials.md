## **AUTH-003:** User Login Invalid Credentials  

> **Summary:** User Login Invalid Credentials verification.  <br>

**Preconditions:** User is on the login page.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Enter correct email format but wrong password.     | Verify text fields display input.                  |
 |  2 | Tap 'Sign In' button.                              | Verify loading indicator displays and then turns off, showing an 'Invalid credentials' toast notification. |  

**Post-conditions:**  

 - No session is established; local cache remains unauthenticated.  
