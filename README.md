# 💊 Pharmacy Management Database (PostgreSQL)

## 📌 Project Overview
This project is a beginner-to-intermediate SQL database designed to simulate
a real-world pharmacy management system.

It manages:
- Patients
- Medicines
- Suppliers
- Prescriptions
- Sales
- Stock control

Built using PostgreSQL and pgAdmin.

---

## 🛠 Tools Used
- PostgreSQL
- pgAdmin 4
- SQL (DDL, DML, Triggers, Views)

---

## 🗄 Database Features
- Auto-calculated sales totals using triggers
- Automatic stock reduction after dispensing
- Summary views for stock and sales
- Fully normalized relational schema

---

## ⚙️ How to Run
1. Create a PostgreSQL database
2. Run files in this order:
   - `schema.sql`
   - `sample_data.sql`
   - `triggers.sql`
   - `views.sql`
3. Test queries from `queries.sql`

---

## 📊 Sample Views
```sql
SELECT * FROM vw_stock_summary;
SELECT * FROM vw_daily_sales;

## **Connect**

Feel free to connect with me on:

LinkedIn

Twitter
