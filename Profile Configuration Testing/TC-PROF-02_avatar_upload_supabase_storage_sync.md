## **TC-PROF-02:** Avatar Upload Supabase Storage Sync  

> **Summary:** Avatar Upload Supabase Storage Sync verification.  <br>

**Preconditions:** User is signed in and has a profile avatar placeholder visible.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Tap the profile avatar icon in the Profile Edit screen. | Verify that the system image picker opens showing local gallery photos. |
 |  2 | Select a valid image file (PNG/JPG, less than 5MB). | Verify image picker closes and selected preview shows on the avatar card. |
 |  3 | Tap 'Save' and wait for upload progress.           | Verify that avatar is successfully uploaded to Supabase Storage bucket and the profile card renders the new remote URL. |  

**Post-conditions:**  

 - Avatar image is saved under Supabase storage bucket and synced in profile schema.  
