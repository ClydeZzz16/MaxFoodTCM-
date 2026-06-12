## **TC-AUTH-01:** Deep Link Email Sign In Success   

> **Summary:** Deep Link Email Sign In Success  verification.  <br>

**Preconditions:** User has access to their email inbox and a registered account exists.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Launch UbayHarvest application.                    | Verify that the landing page screen with 'Sign In' is shown. |
 |  2 | Enter a valid registered email and click 'Send Magic Link'. | Verify a toast message confirms link sent and app enters waiting state. |
 |  3 | Open email client, locate confirmation email, and click the deep link. | Verify UbayHarvest is launched, session is initialized, and user is redirected to the home dashboard screen. |  

**Post-conditions:**  

 - User session is saved in local storage and active in Supabase auth state.  
