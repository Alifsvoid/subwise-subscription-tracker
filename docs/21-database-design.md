# 21. Database Design

### 1. `users` Table Layout
* **id** (INT, Primary Key, Auto-Increment)
* **username** (VARCHAR(50), Unique, Not Null)
* **password_hash** (VARCHAR(255), Not Null)

### 2. `subscriptions` Table Layout
* **id** (INT, Primary Key, Auto-Increment)
* **user_id** (INT, Foreign Key referencing `users(id)`, On Delete Cascade)
* **service_name** (VARCHAR(100), Not Null)
* **cost** (DECIMAL(10,2), Not Null)
* **billing_cycle** (VARCHAR(20), Not Null) -- values: 'monthly', 'annual'
* **renewal_date** (DATE, Not Null)
