## **TC-TRACK-02:** Order Status Updates Sync Buyer Seller Ends   

> **Summary:** Order Status Updates Sync Buyer Seller Ends  verification.  <br>

**Preconditions:** Order status is currently 'Pending'.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Open buyer tracking view and seller order management screen concurrently. | Verify both views display 'Pending' status.        |
 |  2 | On the seller screen, change order status to 'Preparing'. | Verify status updates to 'Preparing' instantly on the seller screen. |
 |  3 | Observe the buyer tracking view.                   | Verify buyer tracking timeline updates to 'Preparing' in real-time without requiring page refresh. |  

**Post-conditions:**  

 - Order state changes sync bidirectionally using live database/socket replication.  
