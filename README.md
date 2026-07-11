# Smart Loan Eligibility & Management System

## Project Overview

The **Smart Loan Eligibility & Management System** is a MySQL-based database project developed to manage the complete loan process of a banking system. The project stores customer details, employment information, income records, credit scores, loan applications, approved loans, EMI schedules, and payment history.

The system helps determine customer loan eligibility based on income and credit score while maintaining accurate loan and payment records. It demonstrates real-world database design using MySQL and implements advanced SQL concepts.

---

## Features

- Branch Management
- Customer Management
- Employment Details
- Income Management
- Credit Score Management
- Loan Type Management
- Loan Application Management
- Loan Approval Management
- EMI Management
- Payment Management

---

## Database Tables

1. Branch
2. Customer
3. Employment
4. Income
5. Credit_Score
6. Loan_Type
7. Loan_Application
8. Loan
9. EMI
10. Payment

---

## Technologies Used

- MySQL 8.0
- MySQL Workbench
- SQL
- Windows

---

## SQL Concepts Implemented

### DDL
- CREATE DATABASE
- CREATE TABLE
- ALTER TABLE
- DROP TABLE

### DML
- INSERT
- UPDATE
- DELETE

### DQL
- SELECT

### Constraints
- PRIMARY KEY
- FOREIGN KEY
- NOT NULL
- UNIQUE
- CHECK

### Joins
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- SELF JOIN

### SQL Features
- Subqueries
- Correlated Subqueries
- Aggregate Functions
- GROUP BY
- HAVING
- ORDER BY
- LIMIT
- Views
- Stored Procedures
- User Defined Functions
- Triggers
- Transactions (COMMIT, ROLLBACK, SAVEPOINT)
- Window Functions

---

## Project Structure

```
Smart_Loan_System
│
├── Database.sql
├── Tables.sql
├── Insert_Records.sql
├── Queries.sql
├── Procedures.sql
├── Functions.sql
├── Triggers.sql
├── Views.sql
└── README.md
```

---

## Modules

### Branch
Stores branch information.

### Customer
Stores customer personal details.

### Employment
Stores employment and company details.

### Income
Stores monthly and annual income.

### Credit Score
Stores customer credit score.

### Loan Type
Stores available loan types and interest rates.

### Loan Application
Stores customer loan application details.

### Loan
Stores approved/rejected loan details.

### EMI
Stores EMI amount and payment status.

### Payment
Stores EMI payment details.

---

## Functions Implemented

- Calculate EMI
- Loan Eligibility Check
- Annual Income Calculation
- Interest Calculation
- Credit Score Grade
- Loan Category

---

## Stored Procedures

- Get All Customers
- Get Loan Details
- Get Customer By ID
- Approved Loans
- High Income Customers

---

## Triggers

- Credit Score Validation
- Loan Amount Validation
- Update EMI Status After Payment

---

## Sample SQL Operations

- Customer Loan Details
- Highest Loan Amount
- EMI Pending Customers
- Branch-wise Customer Count
- Loan Eligibility Report
- Subqueries with JOIN
- Aggregate Reports
- Payment Reports

---

## Expected Output

- Efficient loan data management
- Customer eligibility verification
- EMI tracking
- Payment monitoring
- Report generation using SQL
- Practical implementation of advanced MySQL concepts

---

## Future Enhancements

- Java Spring Boot Integration
- REST API Development
- React Frontend
- User Authentication
- Loan Prediction using Machine Learning
- Dashboard and Reports

---

## Author

**Marisharagavi K**

MCA Graduate (2026)

Junior Java Full Stack Developer

Skills:
- Java
- Spring Boot
- MySQL
- SQL
- React.js
- HTML
- CSS
- JavaScript
