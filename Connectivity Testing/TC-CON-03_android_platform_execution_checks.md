## **TC-CON-03:** Android Platform Execution Checks  

> **Summary:** Android Platform Execution Checks verification.  <br>

**Preconditions:** An Android mobile device or emulator is running.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Install the release build APK on the Android device. | Verify package installer completes without error.  |
 |  2 | Launch the app, log in, and browse dashboard categories. | Verify app execution is stable without lags or JVM/Dart crashes. |  

**Post-conditions:**  

 - Android apk executes cleanly on target Android platforms.  
