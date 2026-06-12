## **TC-PERF-02:** Application Behavior Under Low Battery Power Modes  

> **Summary:** Application Behavior Under Low Battery Power Modes verification.  <br>

**Preconditions:** Device battery is below 15% and enters low battery/power saver mode.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Browse dashboard listings and chat thread inbox.   | Verify app interface remains responsive.           |
 |  2 | Send a message inside a chat room.                 | Verify message still syncs and persists under restricted power saving states. |  

**Post-conditions:**  

 - State transitions remain stable and synchronize correctly under low-power modes.  
