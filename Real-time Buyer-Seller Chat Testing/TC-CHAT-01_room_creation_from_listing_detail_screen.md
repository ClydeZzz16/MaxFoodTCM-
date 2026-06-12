## **TC-CHAT-01:** Room Creation From Listing Detail Screen  

> **Summary:** Room Creation From Listing Detail Screen verification.  <br>

**Preconditions:** User is signed in and is viewing a product listing owned by another seller.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | On the listing details page, tap the 'Chat with Seller' button. | Verify that a loading progress state displays.     |
 |  2 | Wait for chat room resolution.                     | Verify that a chat room page opens, creating a new room in the `chat_rooms` database table if none existed. |  

**Post-conditions:**  

 - Chat room is initialized in Supabase and resolved to a Chat Room screen.  
