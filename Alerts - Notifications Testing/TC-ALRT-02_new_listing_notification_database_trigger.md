## **TC-ALRT-02:** New Listing Notification Database Trigger  

> **Summary:** New Listing Notification Database Trigger verification.  <br>

**Preconditions:** User A has subscribed to an alert for keyword 'Mangoes'.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Sign in as User B and create a product listing titled 'Fresh Organic Mangoes' under Fruits. | Verify listing is successfully published and synced in products table. |
 |  2 | Check notifications table in Supabase dashboard.   | Verify that a notification row targeting User A is automatically inserted via database trigger function. |  

**Post-conditions:**  

 - Database triggers automatically generate notification items for matching keywords.  
