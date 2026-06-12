## **SEC-002:** Verify Database Rls Policies  

> **Summary:** Verify Database Rls Policies verification.  <br>

**Preconditions:** User has logged in with Standard credentials.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Attempt to make raw Supabase API updates to other profiles or delete listings owned by other sellers. | Verify that Supabase API returns 403 Forbidden or empty updates list. |
 |  2 | Inspect database status.                           | Verify that database records remain unmodified.    |  

**Post-conditions:**  

 - Supabase RLS constraints securely restrict writes to owner profiles/listings only.  
