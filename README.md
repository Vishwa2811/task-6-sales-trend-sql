# Task 6: Sales Trend Analysis Using SQL Aggregations

## 🎯 Objective
The objective of this task was to analyze monthly sales trends by calculating the total revenue and number of orders using SQL. This involved using aggregation and date-based grouping to uncover how the business performed over time.

## 🛠️ Tools Used
- SQL (MySQL / PostgreSQL)
- Any SQL execution platform (e.g., MySQL Workbench, pgAdmin, DB Fiddle)

## 📁 Dataset Details
- Table: online_sales
- Columns:
  - order_id – Unique ID for each order
  - order_date – Date of the order
  - amount – Revenue from the order
  - product_id – Product involved in the order
- Source: [Online Sales Dataset on Kaggle](https://www.kaggle.com/datasets/shreyanshverma27/online-sales-dataset-popular-marketplace-data)

## 📌 Steps Followed

1. Created the online_sales table using SQL DDL.
2. Inserted sample data into the table to simulate real sales transactions.
3. Used SQL aggregate functions to analyze:
   - Monthly Revenue using SUM(amount)
   - Order Volume using COUNT(DISTINCT order_id)
4. Grouped data by month using:
   - MySQL: DATE_FORMAT(order_date, '%Y-%m')
   - PostgreSQL: TO_CHAR(order_date, 'YYYY-MM')
5. Sorted the final result by date for a clean monthly trend output.


## 📄 Files Included
- sales_trend_analysis.sql – Contains the SQL query with aggregation and grouping logic

## 💡 Outcome
- Understood how to use SQL for time-based data aggregation
- Learned the importance of date formatting and groupings in trend analysis
- Gained confidence in writing SQL queries that summarize data over time

## 🔗 References
- Kaggle Dataset: https://www.kaggle.com/datasets/shreyanshverma27/online-sales-dataset-popular-marketplace-data
- W3Schools SQL Documentation
  
