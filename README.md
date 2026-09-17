🍕 Pizza Sales SQL Analysis
SQL Data Analytics Project using MySQL

📌 Project Overview
This project analyzes pizza sales data using MySQL. The analysis uses multiple related CSV datasets to answer business questions related to orders, revenue, pizza prices, sizes, categories, quantities, and sales performance. The project contains 13 SQL analysis questions covering basic to intermediate SQL concepts.

🎯 Project Objective
The main objective of this project is to use SQL to analyze pizza sales data and extract meaningful information from the dataset.

The analysis focuses on:

📦 Order volume
💰 Revenue generation
🍕 Pizza sales
📏 Pizza size preferences
🗂️ Category-wise sales
⏰ Order patterns by hour
📈 Revenue performance
🏆 Top-performing pizza types
🛠️ Tools & Technologies
Tool	Purpose
MySQL	Data analysis and SQL queries
SQL	Data querying and analysis
CSV	Source datasets
GitHub	Project version control and portfolio
📂 Dataset
The project contains four related datasets:

orders.csv – Order date and time information
order_details.csv – Order details and pizza quantities
pizzas.csv – Pizza size and price information
pizza_types.csv – Pizza names, categories, and ingredients
🔍 SQL Analysis
The project answers questions such as:

What is the total number of orders?
What is the total revenue generated?
Which pizza has the highest price?
What is the most common pizza size ordered?
What are the top 5 most ordered pizza types?
What is the total quantity ordered by pizza category?
How are orders distributed by hour?
What is the distribution of pizzas by category?
What is the average number of pizzas ordered per day?
What are the top 3 pizza types based on revenue?
What is the revenue contribution of each category?
How does cumulative revenue change over time?
What are the top 3 pizza types by revenue within each category?
🧠 SQL Concepts Used
SELECT
WHERE
COUNT()
SUM()
AVG()
ROUND()
GROUP BY
ORDER BY
LIMIT
INNER JOIN
Subqueries
Aggregate Functions
Window Functions
RANK()
PARTITION BY
📁 Project Structure

🍕 pizza-sales-sql-analysis │ ├── 📂 data │ ├── orders.csv │ ├── order_details.csv │ ├── pizzas.csv │ └── pizza_types.csv │ ├── 📂 sql │ └── pizza_sales_analysis.sql │ ├── 📂 Quaries Output screenshot │ └── 📄 README.md

🔗 Dataset Relationships
orders │ │ order_id ↓ order_details │ │ pizza_id ↓ pizzas │ │ pizza_type_id ↓ pizza_types

Author
Utkarsh Pathak

License
This project is licensed under the MIT Lisence.
