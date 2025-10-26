# ElevateLabs_Task2_SQLforDataAnalysis
Use SQL queries to extract and analyze data from a database.

# 🧮 Elevate Labs – Task 4: SQL for Data Analysis

## 🎯 Objective
Use SQL to extract, analyze, and summarize business data from a retail e-commerce dataset.


## 🧰 Tool Used
**SQLite** (via DB Browser for SQLite)  


## 📊 Dataset
**File:** `data.csv`  
Contains columns:  
`InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country`  
Each record represents an order line from an online retail store.

## 🪜 Steps Followed
1. Imported `data.csv` into SQLite (table name: `orders`).
2. Checked data types and removed any blank rows.
3. Created indexes on CustomerID, InvoiceDate, Country.
4. Wrote SQL queries covering:
   - SELECT, WHERE, ORDER BY, GROUP BY, HAVING
   - Aggregate functions (SUM, AVG, COUNT)
   - Subqueries and CTEs (WITH)
   - Views for reusable analysis
   - Indexing for optimization
5. Saved all queries in `task4_queries.sql`.
6. Captured output screenshots for each major query.

## 🧩 Key Queries
| # | Topic | SQL Concept |
|---|--------|-------------|
| 1 | Total Sales | SUM() |
| 2 | Sales by Country | GROUP BY + ORDER BY |
| 3 | Monthly Sales Trend | SUBSTR(Date) + GROUP BY |
| 4 | Top 10 Products | Aggregation + LIMIT |
| 5 | Top Customers | GROUP BY + ORDER BY |
| 6 | Revenue > Average | Subquery + CTE |
| 7 | Countries > 10 000 Sales | HAVING |
| 8 | Monthly View | CREATE VIEW |

## 🧠 Learnings
- Difference between **WHERE** and **HAVING**
- How to use **GROUP BY** and aggregate functions for summary analysis
- Using **JOINs** and **subqueries** for complex conditions
- Creating **views** for reusable insights
- Improving performance with **indexes**

## 📈 Visual Insights

| Chart | Description |
|--------|--------------|
| **Sales by Country** | Shows the top 10 countries with highest sales. |

This chart was created using **DB Browser Plot tool** .


## 📁 Repository Structure

| File / Folder | Description |
| :-- | :-- |
| `data.csv` | The raw e-commerce dataset used for SQL analysis. |
| `task4_queries.sql` | File containing all SQL queries executed during analysis. |
| `screenshots/` | Folder containing screenshots of SQL query outputs and chart from DB Browser. |
| `README.md` | Project summary file explaining the objectives, process, and results. |


---
*Created by Komal for the Data Analyst Internship Program.*
