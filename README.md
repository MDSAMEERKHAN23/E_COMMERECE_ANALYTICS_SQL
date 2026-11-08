# E-Commerce Sales Analysis Using SQL

## 📌 Project Overview

This project focuses on analyzing an e-commerce business using SQL and PostgreSQL. The main objective is to explore sales performance, customer purchasing behavior, product profitability, payment trends, and delivery performance.

I created a relational database containing multiple interconnected tables and used SQL queries to answer real-world business questions and generate meaningful insights.

## 🎯 Project Objectives

- Analyze overall sales and revenue performance.
- Identify top-performing products and categories.
- Understand customer purchasing behavior.
- Analyze payment methods and refund amounts.
- Calculate order cancellation rates.
- Evaluate shipping company performance.
- Identify delayed deliveries and delivery trends.

## 🗄️ Database Structure

The project contains six tables:

| Table Name | Description |
|---|---|
| Customers | Contains customer details, age, gender, city, and signup date. |
| Orders | Contains order dates, customer IDs, order status, and payment methods. |
| Orders_Item | Contains product quantities, prices, discounts, sales, costs, and profit. |
| Product | Contains product names, categories, subcategories, and pricing information. |
| Payments | Contains payment amounts, payment methods, payment status, and payment dates. |
| Shipment | Contains shipping companies, warehouse locations, shipping days, and delivery status. |

## 🛠️ Tools & Technologies

- PostgreSQL
- SQL
- pgAdmin 4

## 📊 SQL Concepts Used

**1. Data Retrieval**
- SELECT
- DISTINCT
- WHERE
- ORDER BY
- LIMIT

**2. Aggregate Functions**
- SUM()
- COUNT()
- AVG()
- ROUND()

**3. Data Grouping**
- GROUP BY
- HAVING

**4. Joins**
- INNER JOIN
- Connecting multiple tables to perform business analysis.

**5. Conditional Logic**
- CASE WHEN
- Filtering records based on business conditions.

**6. Window Functions**
- RANK()
- PARTITION BY

## 🔍 Business Questions Solved

### Sales Performance Analysis
- What is the total revenue generated?
- What is the total profit?

LINK: https://github.com/MDSAMEERKHAN23/E_COMMERECE_ANALYTICS_SQL/blob/main/e_commerce_sales_analysis.sql
