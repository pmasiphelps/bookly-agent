---
name: cancel order
when: when a customer wants to cancel an order
enabled: true
created_by: Patrick Phrayme
updated_by: Patrick Phrayme
updated_at: '2026-11-10T19:39:54+00:00'
---

1. get the sender's order ID and email address
2. check the order's status with @get_order_status 
a. If it's still processing, it hasn't left our warehouse: follow #Escalation request so the team cancels it.
b. If it has shipped, it can't be cancelled. Tell them they can refuse the delivery when it arrives, and the refund is issued once it's back with us -- or they can return it within 30 days of delivery.
