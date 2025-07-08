SQL for Data Analysis – Task 3
🔍 Objective
This project focuses on using SQL to extract, manipulate, and analyze data from a structured eCommerce database. The main goal is to understand and practice SQL operations including filtering, joining, grouping, and aggregating data.

🛠 Tools Used
MySQL Workbench

MySQL Server

SQL Language

📦 Dataset Structure
The project uses a sample eCommerce database with the following tables:

customers (customer_id, name, country)

products (product_id, name, category, price)

orders (order_id, customer_id, order_date, total_amount)

order_items (item_id, order_id, product_id, quantity)

✅ SQL Concepts Practiced
SELECT statements to view and filter data

WHERE clause for conditional queries

ORDER BY to sort data

JOINs (INNER, LEFT) to combine data across tables

GROUP BY and aggregate functions (SUM, AVG)

Subqueries for advanced filtering

Creating and querying VIEWS

Creating INDEXES for query optimization

📁 Files Included
ecommerce_analysis.sql — contains all SQL queries used for analysis

Screenshots folder — output screenshots for each query result

README.md — this file

🧪 Sample Queries
Example of JOIN query:

sql
Copy
Edit
SELECT o.order_id, c.name, o.total_amount
FROM orders o
JOIN customers c ON o.customer_id = c.customer_id;
Example of aggregate function:

sql
Copy
Edit
SELECT SUM(total_amount) AS total_revenue FROM orders;
📝 Outcome
Learned to write optimized SQL queries

Understood the importance of database relationships

Gained experience in analyzing structured data using SQL

🙋 Author
Name: Karthikeyan

Project: Task 3 – CodeSoft SQL Internship Task
