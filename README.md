# Jeevan_Raksha_Project
Jeevan Raksha Pharmacy – A complete MySQL database project for pharmacy management including schema design, relationships, sample datasets, and SQL queries from basic to advanced.

# 💊 Jeevan Raksha Pharmacy Database Project

A real-world **MySQL database project** built to simulate the management system of a pharmacy store. This project demonstrates database design, table relationships, business logic implementation, data insertion, and SQL query solving from beginner to advanced level.

## 📌 Project Overview
Jeevan Raksha Pharmacy is designed to manage:
- Customers purchasing medicines
- Suppliers providing pharmacy stock
- Medicine inventory with expiry tracking
- Orders/Bills with payment methods
- Order item details for each transaction

This project helps understand how SQL databases are used in **real business applications**.

## 🗂 Database Schema
The project contains the following tables:

### 1. Customers
Stores customer details:
- Customer ID
- Name
- Phone
- City

### 2. Suppliers
Stores supplier information:
- Supplier ID
- Supplier Name
- Contact Person
- Phone

### 3. Medicines
Stores medicine inventory:
- Medicine ID
- Name
- Category
- Price
- Stock Quantity
- Expiry Date
- Supplier ID (Foreign Key)

### 4. Orders
Stores billing details:
- Order ID
- Customer ID (Foreign Key)
- Order Date
- Total Amount
- Payment Mode

### 5. Order Items
Stores ordered medicines:
- Item ID
- Order ID (Foreign Key)
- Medicine ID (Foreign Key)
- Quantity
- Subtotal

## 🔗 Relationships Used
- One Customer → Many Orders
- One Supplier → Many Medicines
- One Order → Many Order Items
- One Medicine → Many Order Items

## 💻 SQL Concepts Covered
✔ DDL Commands (CREATE DATABASE, CREATE TABLE)  
✔ DML Commands (INSERT)  
✔ SELECT Queries  
✔ WHERE Clause  
✔ ORDER BY  
✔ GROUP BY  
✔ HAVING  
✔ Aggregate Functions  
✔ JOINS  
✔ Subqueries  
✔ Foreign Keys & Referential Integrity

## 📊 Sample Query Tasks
- Retrieve customer details
- Find medicines by category
- Analyze payment modes
- Revenue calculation
- Best selling medicine
- Customer lifetime value
- Inventory audit
- Supplier-based medicine count

## 🛠 Technologies Used
- MySQL
- SQL
- Relational Database Design

## 🚀 Learning Outcome
This project improved my understanding of:
- Real-world database modeling
- Writing optimized SQL queries
- Handling relationships between tables
- Business data analysis using SQL

## 📌 Future Improvements
- Add Stored Procedures
- Add Views
- Add Triggers
- Build Frontend UI using Java/Python
- Connect with Backend APIs

## 👨‍💻 Author
**Shaik Bashi**

Learning SQL by building real-world projects 🚀
