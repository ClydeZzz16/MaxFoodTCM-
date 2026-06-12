## **TC-ALRT-04:** Notification Center Badge Read Marks  

> **Summary:** Notification Center Badge Read Marks verification.  <br>

**Preconditions:** User has unread notifications.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Observe navigation menu bar.                       | Verify that notification center icon shows a red badge counter representing unread count (e.g. '3'). |
 |  2 | Tap notification icon to open Notification Center, and click on an unread item. | Verify details open and red badge counter decrements by 1 interactively. |  

**Post-conditions:**  

 - Notification list read statuses update dynamically on client and server.  
