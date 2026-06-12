## **TC-CON-01:** Network Switching Wifi To Cellular Lte 5G   

> **Summary:** Network Switching Wifi To Cellular Lte 5G  verification.  <br>

**Preconditions:** App is active and user is downloading listing images.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Switch device network from WiFi connection to cellular 4G/5G/LTE. | Verify app handles network switch without crashing. |
 |  2 | Continue browsing listings and images feed.        | Verify images finish loading and state sync recovers connection seamlessly. |  

**Post-conditions:**  

 - Active session is retained during network handover operations.  
