# e-commerce-management-system
E-Commerce Order Management System
About the Project

The E-Commerce Order Management System is a database management project developed using MySQL 8.0+. It is designed to manage customers, products, categories, orders, order items, payments, and order status history.

The project demonstrates practical SQL concepts, including database design, constraints, joins, triggers, stored procedures, transactions, indexes, and reporting queries.

Technologies Used
MySQL 8.0+
SQL
MySQL Workbench
Database Tables
users – Stores customer information.
categories – Stores product categories.
products – Stores product details, prices, and stock quantities.
orders – Stores customer orders and shipping details.
order_items – Stores products associated with each order.
payments – Stores payment methods, amounts, and statuses.
order_status_log – Maintains an audit trail of order status changes.
Features
Customer and product management.
Product categorization and stock tracking.
Order creation and order history.
Automatic order total calculation using triggers.
Order status change auditing.
Stored procedures for retrieving order history and creating orders.
Transaction-based order creation with stock validation.
Indexes for improved query performance.
20 SQL queries for sales analysis and reporting.
How to Run
Install MySQL Server 8.0 or later.
Open MySQL Workbench.
Open ecommerce_order_management.sql.
Execute the SQL script to create the database and insert sample data.
Run the reporting queries to explore the results.
Example Query

Retrieve the order history of a customer:

CALL sp_GetUserOrders(1);


Create a sample order:

CALL sp_CreateOrder(
    1,
    2,
    1,
    'Kasturba Gandhi Marg, Delhi',
    'UPI'
);

SQL Concepts Demonstrated
Primary keys and foreign keys
Constraints and data integrity
Joins and subqueries
Aggregate functions and grouping
Triggers
Stored procedures
Transactions and rollback
Indexing and query optimization
Sales reporting and data analysis
Future Enhancements
Product reviews and ratings
Shipment tracking
Discount and coupon management
Enhanced payment and refund processing
Web application integration
Project Information
Project Name: E-Commerce Order Management System
Database: MySQL 8.0+
Project Type: SQL Database Management System
