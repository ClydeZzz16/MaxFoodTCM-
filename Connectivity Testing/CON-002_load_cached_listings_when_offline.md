## **CON-002:** Load Cached Listings When Offline  

> **Summary:** Load Cached Listings When Offline verification.  <br>

**Preconditions:** Device is completely offline.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Launch app and inspect dashboard.                  | Verify that previously cached listings display from local storage cache. |
 |  2 | Attempt to upload profile avatar photo.            | Verify that error snackbar appears informing the user that action requires network connection. |  

**Post-conditions:**  

 - Offline mode displays cached elements and blocks remote changes safely.  
