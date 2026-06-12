## **PROF-002:** Upload Avatar Image To Storage  

> **Summary:** Upload Avatar Image To Storage verification.  <br>

**Preconditions:** User is logged in.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Tap profile avatar edit button.                    | Verify system image gallery chooser opens.         |
 |  2 | Select a photo and tap save.                       | Verify upload progress completes, photo is stored in Supabase Storage avatar bucket, and avatar displays new picture. |  

**Post-conditions:**  

 - Avatar path URL updates in profiles table, pointing to uploaded remote file.  
