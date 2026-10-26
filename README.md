# SQL
# 🗄️ SQL Retail & Sales Data Analysis Project

### 🟢 Data Technician Bootcamp | Week 3 – Databases & SQL

![SQL](https://img.shields.io/badge/SQL-Database_Queries-blue)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Data_Analysis-316192)
![Supabase](https://img.shields.io/badge/Supabase-Database-brightgreen)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## 🌟 Project Overview

This project was completed during **Week 3 of my Data Technician Bootcamp**, focusing on using **Structured Query Language (SQL)** to retrieve, manipulate and analyse structured datasets.

Working with the **Northwind Traders retail database** using Supabase, I developed practical SQL querying skills to explore customer information, product inventories, orders, suppliers and sales-related records.

The objective was to transform raw database records into meaningful business information that could support **sales analysis, marketing decisions, inventory management and operational reporting**.

## 🛠️ Tools & Technologies

- 🟢 **SQL** – Data extraction, filtering and analysis
- 🔵 **PostgreSQL / Supabase** – Relational database querying
- 🟠 **Northwind Database** – Retail and sales data
- 🟣 **Relational Database Concepts** – Primary keys, foreign keys and table relationships
- 🟡 **SQL Aggregations** – COUNT, SUM, AVG and GROUP BY

---

## 🚀 Key Skills Demonstrated

### 🔍 1. Data Retrieval & Filtering

- Used `SELECT` and `FROM` to retrieve customer, product and order records.
- Applied `WHERE` to filter records using business requirements.
- Used `AND`, `OR`, `IN` and `BETWEEN` to build more specific queries.
- Applied `DISTINCT` to identify unique customer locations.
- Used `ORDER BY` to sort products by price and orders by date.

### 📊 2. Data Aggregation & Analysis

Developed skills in summarising datasets using SQL aggregate functions.

- `COUNT()` – Counting records and products within categories.
- `SUM()` – Calculating totals from numerical data.
- `AVG()` – Analysing average prices and other metrics.
- `GROUP BY` – Grouping records to compare performance across categories.
- `ORDER BY` – Ranking and organising analytical results.

These techniques support retail reporting by making it easier to understand product distribution, inventory levels and sales patterns.

### 🔗 3. SQL JOINs & Relational Databases

Explored different SQL JOIN operations to combine information stored across related tables:

- 🟢 **INNER JOIN** – Returning matching records from related tables.
- 🔵 **LEFT JOIN** – Returning all records from the left table and matching records from the right.
- 🟠 **RIGHT JOIN** – Returning all records from the right table and matching records from the left.
- 🟣 **FULL JOIN** – Returning matched and unmatched records from both tables.
- 🟡 **CROSS JOIN** – Generating combinations of records across tables.

Applied JOIN concepts to analyse relationships between products, suppliers, categories and order details.

### 🛍️ 4. Retail & Sales Data Analysis

Worked through business scenarios using the Northwind Traders database, including:

- Retrieving customer information to support marketing campaigns.
- Filtering high-value products based on selling prices.
- Identifying customers across different countries and cities.
- Examining recent orders using date-based sorting.
- Linking products to their suppliers.
- Analysing products by category and quantities ordered.

### 🏗️ 5. Database Design & Data Relationships

- Designed a relational database structure for a training organisation.
- Identified primary and foreign keys.
- Defined one-to-many relationships between tables.
- Explored the differences between relational SQL databases and NoSQL databases.
- Developed an understanding of how structured databases improve data consistency and reporting.

---

## 💻 Example SQL Queries

### 🔹 Retrieve High-Value Products

```sql
SELECT *
FROM Products
WHERE Price > 50
ORDER BY Price DESC;
```

### 🔹 Identify Customers in the UK and USA

```sql
SELECT Customer
```
<img width="541" height="151" alt="image" src="https://github.com/user-attachments/assets/36b01b98-b701-41f6-b01f-f7e8f371620c" />

<img width="551" height="397" alt="image" src="https://github.com/user-attachments/assets/0ffff6b5-5565-4411-a981-d836123a17cd" />

<img width="551" height="409" alt="image" src="https://github.com/user-attachments/assets/88a24864-bdb4-4e45-863a-c1e627d2ed96" />

<img width="562" height="496" alt="image" src="https://github.com/user-attachments/assets/7aadfef9-1e99-467d-a771-652ac1dab37e" />

<img width="548" height="361" alt="image" src="https://github.com/user-attachments/assets/733d42cd-6599-4d8c-a2d0-841858083afc" />

<img width="563" height="362" alt="image" src="https://github.com/user-attachments/assets/9a98a91f-ac83-4ef4-b9c5-3418ff028b68" />

<img width="539" height="311" alt="image" src="https://github.com/user-attachments/assets/615bf96c-8567-49dd-9add-b056e8223a12" />














