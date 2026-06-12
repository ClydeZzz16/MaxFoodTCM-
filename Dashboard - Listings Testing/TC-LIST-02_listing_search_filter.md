## **TC-LIST-02:** Listing Search Filter  

> **Summary:** Listing Search Filter verification.  <br>

**Preconditions:** Multiple listings exist in the database catalog (e.g. Rice, Mangoes, Corn).  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Tap the search searchbar on the home screen.       | Verify text field is focused and keyboard opens.   |
 |  2 | Type 'Mangoes' into the search input.              | Verify the listings feed filters dynamically to display only items containing the keyword 'Mangoes'. |  

**Post-conditions:**  

 - Search query narrows catalog display using client-side or database filter.  
