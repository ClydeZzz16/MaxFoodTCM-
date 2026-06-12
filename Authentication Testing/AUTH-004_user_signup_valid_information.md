## **AUTH-004:** User Signup Valid Information  

> **Summary:** User Signup Valid Information verification.  <br>

**Preconditions:** User is on the signup page.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Enter new name, unique email, and matching password/confirm password fields. | Verify fields accept characters.                   |
 |  2 | Tap 'Sign Up' button.                              | Verify loader displays, account is registered in Supabase auth, and check email message page displays. |  

**Post-conditions:**  

 - Account registration succeeds, entering pending validation state.  
