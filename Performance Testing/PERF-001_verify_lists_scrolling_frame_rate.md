## **PERF-001:** Verify Lists Scrolling Frame Rate  

> **Summary:** Verify Lists Scrolling Frame Rate verification.  <br>

**Preconditions:** Over 100 listings exist in the food marketplace database.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Fling-scroll down the listings feed grid quickly.  | Verify listings list scrolls smoothly (maintaining ~60fps frame rate) without visual stutter. |
 |  2 | Observe scrolling near bottom boundary.            | Verify additional listing pages load lazily and append to layout without freezing the interface thread. |  

**Post-conditions:**  

 - Listings feed grid manages lazy pagination smoothly under high scroll velocities.  
