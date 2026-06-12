## **TC-PERF-03:** Out Of Disk Storage Error Warnings  

> **Summary:** Out Of Disk Storage Error Warnings verification.  <br>

**Preconditions:** Device system storage is completely full.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Attempt to upload a profile avatar picture or download listing detail photos. | Verify app displays clear notification or dialog warning the user of insufficient local disk space. |
 |  2 | Verify app doesn't crash.                          | Confirm that app handles write exception gracefully without sudden process termination. |  

**Post-conditions:**  

 - File write exceptions are handled safely, informing the user of full disk states.  
