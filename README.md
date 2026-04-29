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



# 💊 Jeevan Raksha Pharmacy Management System

## 1. Introduction

Jeevan Raksha Pharmacy Management System is a **database-driven project built using MySQL** to manage pharmacy operations efficiently. The system handles customer information, supplier details, medicine inventory, billing transactions, and ordered items. The main goal of this project is to simulate how a real pharmacy store manages its daily business operations using structured data.

---

## 2. Challenges Faced

During the development of this project, several challenges were encountered:

* Designing proper relationships between multiple tables
* Maintaining **data integrity** using Primary Keys and Foreign Keys
* Managing large datasets for customers, suppliers, medicines, and orders
* Writing optimized SQL queries for business analysis
* Handling inventory management, stock quantity, and medicine expiry dates
* Building meaningful reports such as revenue analysis and best-selling medicines

These challenges helped strengthen understanding of **database normalization and SQL query building**.

---

## 3. System Working

The system works in the following flow:

### Customer Management

Stores customer details such as name, phone number, and city.

### Supplier Management

Maintains supplier information for medicine procurement.

### Medicine Inventory

Tracks:

* Medicine name
* Category
* Price
* Stock Quantity
* Expiry Date
* Supplier Details

### Order Processing

Whenever a customer purchases medicines:

* A new order is created
* Payment mode is recorded (UPI / Cash / Card)
* Total bill amount is calculated
* Ordered medicines are stored in Order Items

### Reporting & Analysis

The database can generate reports like:

* Total revenue by payment mode
* High-value bills
* Best-selling medicine
* Low stock medicines
* Customer spending patterns

---

## 4. Tools & Technologies Used

**Database:** MySQL
**Query Language:** SQL
**IDE / Environment:** MySQL Workbench / VS Code
**Concepts Used:**

* CREATE DATABASE
* CREATE TABLE
* INSERT INTO
* SELECT Queries
* WHERE Clause
* GROUP BY
* HAVING
* ORDER BY
* Aggregate Functions
* INNER JOIN
* Subqueries
* Primary Key & Foreign Key Relationships

---

## 5. Future Enhancements

This project can be enhanced further by adding:

✅ Login Authentication for Admin/Staff
✅ Expiry Medicine Alert System
✅ Automatic Stock Refill Notification
✅ Customer Purchase History Tracking
✅ GST Bill Generation
✅ Dashboard for Sales Analytics
✅ Integration with Java / Python Frontend
✅ Mobile App for Pharmacy Management
✅ Barcode Scanning for Faster Billing

---

## 6. Approach

The development approach followed:

**Step 1:** Understand pharmacy business workflow
**Step 2:** Identify entities (Customers, Suppliers, Medicines, Orders, Order Items)
**Step 3:** Design relational database schema
**Step 4:** Establish relationships using foreign keys
**Step 5:** Insert sample data
**Step 6:** Write SQL queries from basic to advanced level
**Step 7:** Analyze outputs for business insights

This structured approach helped build a scalable and realistic database project.

---

## 7. Conclusion

Jeevan Raksha Pharmacy Management System is a practical implementation of **Relational Database Management using MySQL**. This project demonstrates how SQL can be used not only for storing data but also for generating valuable business insights. It improved skills in **database design, SQL querying, joins, aggregations, and real-world problem solving**.

This project is a strong step toward building complete **full-stack database applications** in the future. 🚀

