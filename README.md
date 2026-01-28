# Financial Transactions & Fraud Detection Analysis (SQL)

## 📌 Project Overview
This project focuses on analyzing financial transaction data to understand transaction patterns, customer behavior, and fraud trends using SQL. The objective is to perform data cleaning, exploratory analysis, and advanced SQL queries to derive meaningful business insights and identify potential fraud risks.

---

## 📊 Dataset
- Source: Kaggle (Financial Transactions Dataset)
- Format: CSV
- The dataset includes:
  - Transaction ID and Customer ID
  - Transaction Date and Amount
  - Transaction Type and Merchant
  - Country information
  - International transaction flag
  - Fraud indicator

---

## 🧹 Data Cleaning & Preparation
- Verified schema and column consistency
- Converted transaction date-time into proper date format
- Removed time component from transaction dates
- Created derived columns (day, month) for time-based analysis
- Checked for duplicate records and invalid values

---

## 🔍 Key Analysis Performed

### Beginner Analysis
- Total number of transactions
- Total and average transaction amount
- Unique customers and countries
- International vs domestic transaction comparison
- Minimum and maximum transaction values
- Daily transaction count trends

### Intermediate Analysis
- Transaction amount by country
- Merchant-wise revenue analysis
- Fraud percentage calculation
- Fraud comparison across countries
- Customer spending analysis
- Month-wise transaction trends
- Fraud comparison between international and domestic transactions

### Advanced Analysis
- Identification of high-risk merchants based on fraud rate
- Detection of unusually large transactions
- Customers with repeated fraud transactions
- Country ranking based on fraud rate
