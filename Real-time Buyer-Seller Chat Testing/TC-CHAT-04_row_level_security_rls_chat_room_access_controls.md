## **TC-CHAT-04:** Row Level Security Rls Chat Room Access Controls  

> **Summary:** Row Level Security Rls Chat Room Access Controls verification.  <br>

**Preconditions:** User A and User B belong to Chat Room X. User C is an external user.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Sign in as User C.                                 | Verify user is logged in successfully.             |
 |  2 | Attempt to fetch or write messages for Chat Room X via Supabase API commands. | Verify that Supabase API returns a 'Permission Denied' or empty list error, blocking access. |  

**Post-conditions:**  

 - Supabase Row-Level Security (RLS) policies successfully restrict chat channel reads/writes to room participants.  
