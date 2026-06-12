## **AUTH-002:** User Login Invalid Email Format  

> **Summary:** User Login Invalid Email Format verification.  <br>

**Preconditions:** User is on the login page.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Enter an invalid email format (e.g. 'not-an-email') and password. | Verify fields display entered text.                |
 |  2 | Tap 'Sign In' button.                              | Verify signup/signin is blocked and an error toast highlights the email format constraint. |  

**Post-conditions:**  

 - Authentication request is rejected on client-side validation; no request sent to Supabase.  
