## **TC-SEC-01:** Deep Link Auth Token Validation Checks  

> **Summary:** Deep Link Auth Token Validation Checks verification.  <br>

**Preconditions:** User attempts authentication flow.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Attempt to access auth confirmation handler URL with a forged or empty magic link token. | Verify that handler rejects execution.             |
 |  2 | Observe redirection result.                        | Verify that session is rejected and navigation routes to landing page with error toast. |  

**Post-conditions:**  

 - Security token validation blocks access to unauthenticated sessions.  
