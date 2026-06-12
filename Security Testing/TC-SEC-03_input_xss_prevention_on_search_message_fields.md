## **TC-SEC-03:** Input Xss Prevention On Search Message Fields  

> **Summary:** Input Xss Prevention On Search Message Fields verification.  <br>

**Preconditions:** User is typing inside Chat Message input box.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Type `<script>alert('XSS')</script> Hello` into chat input and tap Send. | Verify message is submitted.                       |
 |  2 | Observe message rendering on receiving client's chat screen. | Verify receiving client displays script payload as literal string text instead of executing it as HTML script. |  

**Post-conditions:**  

 - Inputs are escaped or stripped, preventing Cross-Site Scripting (XSS) injections.  
