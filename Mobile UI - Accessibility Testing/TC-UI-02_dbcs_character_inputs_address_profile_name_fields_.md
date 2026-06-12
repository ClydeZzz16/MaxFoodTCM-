## **TC-UI-02:** Dbcs Character Inputs Address Profile Name Fields   

> **Summary:** Dbcs Character Inputs Address Profile Name Fields  verification.  <br>

**Preconditions:** User is editing profile fields.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Set Full Name to double-byte characters 'テストユーザー' (Japanese) or '張三' (Chinese). | Verify input text box accepts inputs correctly.    |
 |  2 | Tap Save and inspect updated database record.      | Verify characters are persisted without encoding distortion, displaying correctly on profile cards. |  

**Post-conditions:**  

 - Form text boxes accept and persist double-byte characters (DBCS) safely.  
