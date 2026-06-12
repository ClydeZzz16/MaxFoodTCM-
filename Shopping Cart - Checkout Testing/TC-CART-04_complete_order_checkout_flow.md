## **TC-CART-04:** Complete Order Checkout Flow  

> **Summary:** Complete Order Checkout Flow verification.  <br>

**Preconditions:** Items exist inside the shopping cart.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Tap the 'Proceed to Checkout' button.              | Verify Checkout screen is shown displaying delivery address and payment fields. |
 |  2 | Confirm delivery address and tap 'Submit Order'.   | Verify a success overlay displays, the order is registered in Supabase database, and cart is cleared. |  

**Post-conditions:**  

 - Order is recorded in the orders table, and local cart state resets to empty.  
