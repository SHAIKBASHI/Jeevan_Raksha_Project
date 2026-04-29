# 💊 Jeevan_Raksha_Project

**Jeevan Raksha Pharmacy** is a real-world **MySQL database project** built to simulate pharmacy management operations such as customer handling, supplier management, inventory tracking, billing, and sales analysis.

---

## 📌 Introduction

This project is designed to manage:

* Customers purchasing medicines
* Suppliers providing pharmacy stock
* Medicine inventory with expiry tracking
* Orders/Bills with payment methods
* Order item details for each transaction

The goal is to understand how relational databases solve real business problems.

---

## 🗂 Database Schema

The project contains 5 main tables:

### 1. Customers

* Customer ID
* Name
* Phone
* City

### 2. Suppliers

* Supplier ID
* Supplier Name
* Contact Person
* Phone

### 3. Medicines

* Medicine ID
* Name
* Category
* Price
* Stock Quantity
* Expiry Date
* Supplier ID (Foreign Key)

### 4. Orders

* Order ID
* Customer ID (Foreign Key)
* Order Date
* Total Amount
* Payment Mode

### 5. Order Items

* Item ID
* Order ID (Foreign Key)
* Medicine ID (Foreign Key)
* Quantity
* Subtotal

---

## 🔗 Relationships Used

* One Customer → Many Orders
* One Supplier → Many Medicines
* One Order → Many Order Items
* One Medicine → Many Order Items

---

## ⚡ Challenges Faced

* Designing proper table relationships
* Maintaining data integrity using Primary & Foreign Keys
* Managing large datasets
* Writing optimized SQL queries
* Handling stock & expiry tracking
* Creating business reports from raw data

---

## ⚙ System Working

The system performs:
✔ Customer Management
✔ Supplier Management
✔ Medicine Inventory Tracking
✔ Order Processing & Billing
✔ Payment Mode Tracking
✔ Revenue Analysis
✔ Best Selling Medicine Analysis
✔ Inventory Audit Reports

---

## 💻 Tools & Technologies Used

* **Database:** MySQL
* **Language:** SQL
* **Concepts:**

  * CREATE DATABASE / TABLE
  * INSERT INTO
  * SELECT Queries
  * WHERE Clause
  * GROUP BY / HAVING
  * ORDER BY
  * Aggregate Functions
  * JOINS
  * Subqueries
  * Primary & Foreign Keys

---

## 🚀 Approach

1. Understand pharmacy workflow
2. Identify entities
3. Design schema
4. Create relationships
5. Insert sample data
6. Build SQL queries
7. Generate reports & insights

---

## 📊 Sample Query Tasks

* Customer List
* Stock Check
* High Value Bills
* Payment Analysis
* Revenue Calculation
* Best Selling Medicine
* Customer Lifetime Value
* Inventory Audit

---

## 🔮 Future Enhancements

✅ Admin Login
✅ Expiry Alerts
✅ Auto Stock Refill
✅ Customer Purchase History
✅ GST Bill Generation
✅ Sales Dashboard
✅ Frontend Integration (Java / Python)
✅ Mobile App Support
✅ Barcode Billing

---

## 🎯 Conclusion

This project strengthened my understanding of **database design, SQL querying, joins, subqueries, aggregations, and real-world business logic implementation**. It serves as a strong foundation for future full-stack database applications.

---

## 👨‍💻 Author

**Shaik Bashi**
*Learning SQL by building real-world projects 🚀*
