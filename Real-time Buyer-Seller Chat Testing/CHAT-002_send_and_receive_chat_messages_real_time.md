## **CHAT-002:** Send And Receive Chat Messages Real Time  

> **Summary:** Send And Receive Chat Messages Real Time verification.  <br>

**Preconditions:** A chat room screen is open between buyer and seller.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Type 'Is this food item still fresh?' in message field and tap Send. | Verify message bubble displays immediately on screen with pending indicator and updates to sent. |
 |  2 | Observe seller's chat view in real-time.           | Verify that the message appears instantly on the seller's chat room screen without manual refreshes. |  

**Post-conditions:**  

 - Messages sync dynamically over Supabase Realtime channel subscriptions.  
