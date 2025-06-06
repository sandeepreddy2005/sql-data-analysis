# SQL for Data Analysis 🧠📊

## 📁 Objective
Use SQL queries to extract, analyze, and generate insights from a relational e-commerce database. The focus is on applying SQL techniques such as filtering, aggregation, joins, subqueries, views, and optimization.

---

## 🛠 Tools Used
- SQL Engine: MySQL / PostgreSQL / SQLite *(choose one)*
- Interface: MySQL Workbench / pgAdmin / DB Browser for SQLite *(based on tool used)*

---

## 🧾 Dataset
**Ecommerce_SQL_Database.sql**  
This dataset simulates an ecommerce business with the following sample tables:
- `customers`
- `orders`
- `order_items`
- `products`
- `categories`

---

## 🔍 Key SQL Concepts Covered

### ✅ SELECT, WHERE, ORDER BY
- Example: Retrieve products with price greater than 100.
```sql
SELECT * FROM products WHERE price > 100 ORDER BY price DESC;
