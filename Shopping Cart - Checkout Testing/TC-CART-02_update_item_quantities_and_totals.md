## **TC-CART-02:** Update Item Quantities And Totals  

> **Summary:** Update Item Quantities And Totals verification.  <br>

**Preconditions:** An item exists inside the shopping cart.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Tap the '+' button next to the item quantity.      | Verify quantity counter increments to 2 and cart subtotal/total recalculate correctly. |
 |  2 | Tap the '-' button next to the item quantity.      | Verify quantity counter decrements to 1 and totals update. |  

**Post-conditions:**  

 - Cart state manages item quantities reactively and computes totals accurately.  
