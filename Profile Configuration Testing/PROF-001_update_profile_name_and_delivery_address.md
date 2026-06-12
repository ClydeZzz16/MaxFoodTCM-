## **PROF-001:** Update Profile Name And Delivery Address  

> **Summary:** Update Profile Name And Delivery Address verification.  <br>

**Preconditions:** User is logged in.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to Profile screen and tap 'Edit Profile'. | Verify profile details load in text fields.        |
 |  2 | Update Name to 'Clyde Egmilan' and Delivery Address to 'Ubay, Bohol', then tap Save. | Verify progress bar completes, profile card displays updated data, and changes sync in Supabase. |  

**Post-conditions:**  

 - Profile updates persist in profiles database table, and Riverpod state is refreshed.  
