# 🛒 Shopping Mania – Retail Management Database System

**Shopping Mania** is a fully normalized retail management system designed as part of a DBMS course project. It simulates the backend operations of a departmental store, including inventory, billing, supplier management, and employee administration, using SQL and relational database principles.

---

## 🧱 Project Highlights

- 🔧 **Fully normalized schema** across 13+ relational tables (all in BCNF).
- 🗃️ Includes employee hierarchy, supplier network, customer billing, item tracking, return/warranty, and discount offers.
- 📤 Data population with realistic insertions across multiple dimensions (employees, items, bills, orders, etc.).
- 📈 35+ insightful analytical queries to support decision-making (e.g., top customers, sales trends, product performance).
- ✅ ER diagram and normalization proofs provided.

---

## 🧩 Features & Entities

### 👥 Employees & Sections
- Tracks employee data, shifts, and supervisors.
- Supports multi-manager sections via foreign key links.

### 🛍️ Inventory & Sales
- Items categorized by section and tracked by stock, price, and sales.
- Detailed bill and transaction tracking with return and warranty policies.

### 📦 Suppliers & Orders
- Maintains supplier contacts, emails, and purchase order histories.
- Supports discounts, order arrival tracking, and restocking logic.

### 💳 Customers & Billing
- Captures customer details, payment modes, and multi-item billing.
- Supports analysis of top spenders, payment trends, and purchase gaps.

---

## 🧪 Sample Analytical Queries

- Total sales per item and section
- Employees with longest tenure
- Top 5 most profitable sections
- Items restocked or returned in a given month
- Highest-spending customers and most sold products
- Warranty, refund, and offer performance insights

---

## 🧰 Tech Stack

- **Database**: PostgreSQL / MySQL
- **Language**: SQL (DDL, DML, Queries)
- **Design Tools**: ER modeling, Normalization proofs (BCNF)

---
