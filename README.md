# Ecommerce-business-analysis
Project Overview
This project involves designing and analyzing an E-commerce relational database using SQL. The database includes customer, product, order, order_items, and payment tables to simulate real-world business operations. SQL queries were written to generate insights such as revenue trends, customer spending behavior, and best-selling products.
Database Design
The database consists of the following tables:
Customers Table
Products Table
Orders Table
Order_Items Table
Payments Table
These tables are connected using primary and foreign keys to maintain relational integrity.
Data Creation
Sample datasets (20 rows per table) were inserted to simulate realistic business transactions including:
Customer details
Product pricing
Order records
Payment information
Quantity purchased per order
Analysis Queries Performed
The following business insights were generated using SQL queries-
1️⃣ Total Revenue
Calculated overall revenue from the payments table using aggregation functions.
2️⃣ Revenue by Product
Identified revenue contribution of each product using JOIN operations and GROUP BY.
3️⃣ Top Customers by Spending
Detected high-value customers based on total purchase amount.
4️⃣ Best Selling Products
Analyzed product demand using quantity aggregation.
5️⃣ Cancelled Orders Count
Measured number of cancelled orders to evaluate order completion trends.
SQL Concepts Used
This project demonstrates practical usage of:
CREATE TABLE
INSERT INTO
PRIMARY KEY & FOREIGN KEY
INNER JOIN
GROUP BY
ORDER BY
SUM()
COUNT()
Aggregation techniques
Tools Used
MySQL
MySQL Workbench
Project Outcome
Designed a structured relational database and performed business-focused SQL analysis to extract insights related to:
revenue performance
customer purchase behavior
product demand trends
order cancellation tracking
