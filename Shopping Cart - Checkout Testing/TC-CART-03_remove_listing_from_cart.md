## **TC-CART-03:** Remove Listing From Cart  

> **Summary:** Remove Listing From Cart verification.  <br>

**Preconditions:** An item exists inside the shopping cart.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Tap the trash/delete icon on the item card.        | Verify item is removed from the cart screen immediately and cart badge decrements. |
 |  2 | Observe empty cart layout.                         | Verify 'Your cart is empty' illustration is shown. |  

**Post-conditions:**  

 - Item is removed from local cart list state.  
