# Indian-Banking-Transactions-Analysis Using Advanced Excel
Indian Banking Transactions Analysis using Advanced Excel – Data Cleaning, PivotTables, Dashboard and Business Insights.


This folder contains the original and cleaned banking transaction datasets.

## 1. Project Overview

This project focuses on analyzing Indian banking transaction data using Microsoft Excel. The main objective is to understand transaction trends, identify suspicious transactions, analyze payment methods, and present meaningful business insights through an interactive Excel dashboard.

## 2. Problem Statement

Banks handle a large number of transactions through different branches, regions and payment channels. Analyzing this information helps identify transaction patterns, monitor fraud, understand customer activity and improve banking operations.

This project uses Excel to clean, analyze and visualize banking transaction data.

## 3. Project Objectives

- Analyze transaction trends across different regions and branches.
- Identify duplicate records and missing values.
- Analyze deposits, withdrawals and transfers.
- Identify fraudulent transactions.
- Evaluate payment mode usage.
- Analyze transaction statuses such as Completed, Failed and Reversed.
- Create an interactive dashboard to present key findings.

## 4. Tools and Technologies

- Microsoft Excel
- Excel Formulas
- Conditional Formatting
- Data Validation
- PivotTables
- Charts and Dashboard

## 5. Dataset Description

The dataset contains 500 banking transaction records.

Important fields include:

- Transaction ID
- Customer ID
- Customer Name
- Account Number
- Region
- City
- Branch Name
- Account Type
- Transaction Type
- Transaction Amount
- Payment Mode
- Transaction Date
- Transaction Status
- Balance After Transaction
- Is Fraud

Additional derived columns were created for further analysis.

## 6. Data Cleaning and Preparation

The following activities were performed:

- Checked and removed duplicate Transaction IDs.
- Identified missing values.
- Checked negative transaction amounts and account balances.
- Checked transaction date validity.
- Reviewed text consistency.
- Created additional analytical columns.

## 7. Derived Columns

- **Year-Month:** Extracts the year and month from the transaction date.
- **Net Change:** Represents the positive or negative transaction amount.
- **Fraud Flag:** Assigns 1 for fraudulent transactions and 0 otherwise.
- **Transaction Category:** Classifies UPI transactions as Digital and other payment modes as Other Payment Mode.
- **Customer Type:** Classifies customers as Frequent Transactor or One-Time User.

## 8. Excel Analysis

Six PivotTables were created to analyze:

1. Regional Transaction Volume
2. Monthly Transaction Trends
3. Transaction Type Analysis
4. Payment Mode Analysis
5. Fraud Transactions by Branch
6. Transaction Status Analysis

## 9. Dashboard

The Excel dashboard includes four visualizations:

1. Regional Transaction Volume – Bar Chart
2. Monthly Transaction Trends – Line Chart
3. Payment Mode Usage – Doughnut Chart
4. Fraud Transactions by Branch – Stacked Bar Chart

It also includes KPI cards and key business insights.

## 10. Key Findings

- Total transactions analyzed: 500.
- Fraudulent transactions identified: 13.
- Completed transactions: 434.
- Failed transactions: 26.
- Reversed transactions: 21.
- North region recorded 110 transactions, while East recorded 94.
- November 2023 recorded the highest monthly transaction count, with 28 transactions.
- UPI transactions accounted for 94 records.
- All 500 Customer IDs were unique in the dataset.

## 11. Business Recommendations

- Monitor suspicious transactions regularly.
- Review branches with higher fraud counts.
- Analyze failed and reversed transactions to identify possible operational issues.
- Monitor regional transaction activity.
- Use transaction trends to support banking decisions.

## 12. Project Structure

```text
Indian-Banking-Transactions-Analysis/
│
├── Dataset/
│   ├── Indian_Banking_data.xlsx
│   └── Indian_Banking_Transactions_Analysis.xlsx
│
├── Pivot-Tables/
├── Dashboard/
├── Screenshots/
└── README.md
```

## 13. Conclusion

This project demonstrates how Microsoft Excel can be used for data cleaning, data analysis and visualization. The dashboard provides a clear view of banking transaction patterns and helps identify useful business insights.

## 14. Skills Demonstrated

Microsoft Excel | Data Cleaning | Data Analysis | PivotTables | Data Visualization | Dashboard Development | Business Insights
