## **TC-PROF-01:** Update Profile Fields Name Phone Delivery Address   

> **Summary:** Update Profile Fields Name Phone Delivery Address  verification.  <br>

**Preconditions:** User is signed in and has a valid profile card.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the Profile screen and tap 'Edit Profile'. | Verify edit form field inputs are active.          |
 |  2 | Modify Full Name to 'John Farmer Doe', Phone to '+639123456789', and Address to 'Ubay, Bohol'. | Verify inputs show correct text values.            |
 |  3 | Tap 'Save changes' button.                         | Verify a success snackbar displays and changes are immediately updated on the profile card and synced to Supabase database. |  

**Post-conditions:**  

 - Profile data persists in the database table and Riverpod local state is updated.  
