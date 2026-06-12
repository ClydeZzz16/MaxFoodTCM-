## **TC-PROF-03:** Profile State Cache Reset On Account Switch  

> **Summary:** Profile State Cache Reset On Account Switch verification.  <br>

**Preconditions:** User has active profile credentials cached locally.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Log out of current account and log in with a different email account. | Verify transition succeeds and dashboard displays. |
 |  2 | Navigate to the Profile screen.                    | Verify that previous user's name, phone, and address cache is completely cleared and the new user's profile is loaded from Supabase. |  

**Post-conditions:**  

 - Riverpod auto-invalidates the previous profile state to prevent account credential leaks.  
