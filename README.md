# 🏦 Multi-Product Customer Analysis with SQL

## 📌 Description

This project analyzes a bank’s customer base to identify clients who hold multiple financial products such as accounts, cards, and loans.

The objective is to measure customer depth, engagement level, and product distribution using SQL queries across multiple related tables.

---

## 🧠 Business Problem

The bank does not know how many customers hold multiple financial products or which clients are the most engaged.

Understanding product penetration is essential to:

- Identify high-value customers
- Detect cross-selling opportunities
- Improve customer segmentation
- Support commercial strategy decisions

This project solves that problem through relational SQL analysis.

---

## 🎯 Analysis Objectives

- Identify customers who own all three products (account + card + loan)
- Count customers by product combination:
  - Account only
  - Account + card
  - Account + loan
  - All three products
- Calculate average balance of customers with multiple products
- Analyze city distribution of multi-product customers
- Identify customers with the highest number of products

---

## 🗄️ Data Structure

The analysis is based on four relational tables:

**Customers**
- `customer_id`
- `name`
- `age`
- `city`

**Accounts**
- `account_id`
- `customer_id`
- `account_type`
- `balance`

**Cards**
- `card_id`
- `customer_id`
- `card_type`

**Loans**
- `loan_id`
- `customer_id`
- `loan_amount`

---

## 🛠️ Technologies Used

- SQL
- Relational database
- CSV datasets
- Git
- GitHub

---

## 🧩 Key Learnings

- INNER JOIN vs LEFT JOIN
- Multi-table joins
- Conditional counting
- Customer segmentation
- Business-oriented data analysis

---

## 👤 Author

**Aleksei García Adov**  
Aspiring Data Analyst  

---

## ⭐ About the Project

This project simulates a real-world banking scenario where customer engagement and product penetration are analyzed to identify the most valuable and highly linked clients.

It reflects the type of analysis performed by Data Analysts and CRM-focused Data Scientists in the financial industry.
