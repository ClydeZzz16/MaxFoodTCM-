## **TC-AUTH-02:** Deep Link Email Sign In Invalid Expired Link   

> **Summary:** Deep Link Email Sign In Invalid Expired Link  verification.  <br>

**Preconditions:** User has an expired or modified deep link token.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Click on the expired or tampered deep link confirmation URL. | Verify UbayHarvest application launches.           |
 |  2 | Observe redirection handler execution.             | Verify the app displays an error toast indicating the link is invalid or expired, and redirects the user back to the landing page. |  

**Post-conditions:**  

 - No session is established; local cache remains empty.  
