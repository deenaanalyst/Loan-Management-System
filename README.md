# Loan Management System (MySQL Project)

## 📌 Description
A complete SQL-based project for managing loan data, customer income, CIBIL scores, and interest calculations. Implemented advanced SQL features like triggers, joins, and stored procedures using MySQL.

## 🛠️ Technologies Used
- MySQL
- SQL Triggers (Row & Statement level)
- Joins (Inner Join, Full Join)
- Stored Procedures
- Data Filtering & Classification

## 📁 Dataset Overview
1. **Customer Income Status**
2. **Loan Status**
3. **Customer Information**
4. **Country and State Info**
5. **Region Info**

## 📊 Key Features
- 📌 Classify applicants into Grade A, B, Middle, or Low Class based on income.
- 📈 Calculate dynamic monthly and annual interest rates based on region and income.
- 🔒 Row-level triggers for `loan amount` status updates.
- 📉 Statement-level triggers for evaluating CIBIL scores:
  - >900 = High
  - >750 = No Penalty
  - >0 = Penalty
  - <=0 = Rejected
- 🧹 Delete rejected or still-processing loan applicants.
- 📊 Join multiple datasets to generate unified views.
- 🔍 Filters for high CIBIL score and corporate/home office customers.
- 🧠 Outputs stored as SQL procedures for reusability.

## 🧪 Outputs
- **Customer Interest Analysis Table**
- **Loan CIBIL Score Status Table**
- **Joined Views of All 5 Sheets**
- **Filtered Outputs**
  - High CIBIL Score
  - Corporate & Home Office Customers
- **Stored Procedures for All Filters**

## 📁 Files Included
- `project_description.docx` – Original project problem statement
- `queries.sql` – SQL code (to be added by user)
- `README.md` – This file
- 

## 📌 How to Use
1. Clone or download this repo.
2. Open the SQL files in MySQL Workbench or any SQL IDE.
3. Execute in order: table creation → triggers → procedures → joins → filters.
4. Use the procedures to get output views.

## 👤 Author
**Deenathayalan F**
