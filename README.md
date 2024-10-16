# Indian E-commerce DBMS Project

## Overview
This project demonstrates various SQL concepts implemented within the Indian e-commerce domain. It involves creating a user-defined database with tables related to customers, orders, products, and transactions. The project showcases essential SQL operations such as DDL, DML, TCL, joins, constraints, views, subqueries, and set operators.

## Key Features
- **Entities**: Customers, Orders, Products, Transactions
- **Relationships**: 
  - One-to-Many between Customers and Orders
  - Many-to-Many between Orders and Products
  - One-to-One between Orders and Transactions

## Schema
- **Customers**: Stores customer details (customer_id, name, email, phone_number, city, registration_date)
- **Orders**: Captures order information (order_id, customer_id, order_date, total_amount, payment_status)
- **Products**: Contains product details (product_id, name, category, price, stock_quantity)
- **Transactions**: Manages payment info (transaction_id, order_id, payment_method, payment_date)

## SQL Commands
1. **Table Creation**: Define tables and insert initial data.
2. **Data Manipulation**: Update and rename tables.
3. **Joins and Subqueries**: Execute queries to fetch related data.
4. **Views and Transactions**: Create views for easier data access and manage transactions.
5. **Set Operators**: Combine query results using UNION.

## Installation
Clone the repository and set up a local SQL environment to run the SQL scripts.

```bash
git clone https://github.com/yourusername/indian-ecommerce-dbms.git
