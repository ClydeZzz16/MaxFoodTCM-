## **TC-AUTH-04:** Navigation Redirection Protected Routes   

> **Summary:** Navigation Redirection Protected Routes  verification.  <br>

**Preconditions:** User is unauthenticated.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Launch application and attempt to navigate to a protected route URL (e.g., `/profile` or `/chat`). | Verify that GoRouter blocks navigation and redirects the view to the Landing Page. |
 |  2 | Verify dashboard access is inaccessible.           | Confirm that dashboard elements do not render and landing page remains active. |  

**Post-conditions:**  

 - User is restricted to the landing page; no protected state leaks.  
