# STORE-DATABASE
You are responsible for designing a database for an online sales company. There
database will have to manage customers, orders and products. Here are the specifications
:
1. Create a “customers” table including the following fields:
- client_id (primary key)
- name
- first name
- E-mail
- address
- phone
2. Create a “products” table including the following fields:
- product_id (primary key)
- name
- description
- price
- stock
3. Create an “orders” table including the following fields:
- order_id (primary key)
- id_client (foreign key to the “clients” table)
- order_date
- status (in progress, delivered, canceled)
- total
4. Add a CHECK constraint on the "status" field of the "orders" table for you
ensure that only "in progress", "delivered" or "canceled" values are allowed.
5. Set a default value for the "status" field in the "orders" table to "en
course".
