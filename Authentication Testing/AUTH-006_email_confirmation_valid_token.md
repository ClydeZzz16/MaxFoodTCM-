## **AUTH-006:** Email Confirmation Valid Token  

> **Summary:** Email Confirmation Valid Token verification.  <br>

**Preconditions:** User has registered and has signup validation confirmation email.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Open confirmation email and tap the native deep link button. | Verify that the UbayHarvest application launches.  |
 |  2 | Observe redirection execution.                     | Verify that deep link handler validates the confirmation token, initializes the session, and routes to dashboard. |  

**Post-conditions:**  

 - Account email confirmation flag updates to true on server, establishing authenticated session.  
