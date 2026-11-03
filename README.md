# Coffee-Shop-Sales-Analysis-SQL
SQL project analysing coffee sales, customer behaviour, product performance, and city-wise sales trends.


# Coffee Shop Sales Analysis using SQL

## Project Overview
This project focuses on analysing coffee shop sales data using SQL to understand customer behaviour, product performance, revenue trends, and city-wise business performance.

The analysis uses SQL queries to extract meaningful insights and identify potential business opportunities across different cities.

## Tools & Technologies
- SQL
- PostgreSQL

## Database Tables
The project uses the following tables:

- **City:** Contains city-level information.
- **Customers:** Contains customer details.
- **Products:** Contains product information.
- **Sales:** Contains sales transaction records.

## Key Analysis Performed

- Estimated the number of coffee consumers in each city.
- Analysed revenue generated during Q4 2023.
- Compared revenue performance across different cities.
- Identified sales quantities for individual products.
- Calculated average sales per customer by city.
- Compared estimated coffee consumers with actual unique customers.
- Identified the top 3 selling products in each city using `DENSE_RANK()`.
- Analysed unique customers across cities.
- Compared average sales with monthly rental costs.
- Analysed monthly sales growth using the `LAG()` window function.
- Evaluated market potential across cities using sales, rent, and customer data.

## SQL Concepts Used

- SELECT, WHERE, GROUP BY, ORDER BY
- JOINs
- Aggregate Functions
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- DENSE_RANK()
- LAG()
- Date Functions
- CASE Statements

## Project Objective

The objective of this project is to demonstrate how SQL can be used to analyse business data, identify sales patterns, understand customer behaviour, evaluate product performance, and support data-driven business decisions.

## Repository Contents

- `CoffeeShop.sql` – SQL script containing the database analysis queries.

---
**Project Type:** SQL Data Analysis  
**Focus Areas:** Sales Analysis | Customer Insights | Product Performance | Business Analysis
