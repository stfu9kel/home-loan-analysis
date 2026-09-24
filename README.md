# 🏠 Home Loan Analytics & EMI Default Monitoring

## 📌 Project Overview

This project analyzes home loan application, sanction, disbursement, and recovery data to generate meaningful business insights.

The project uses Python and Pandas for data cleaning, data integration, exploratory data analysis, and automated reporting.

The analysis combines multiple related datasets including customer, channel, product, branch, sanction, and recovery information.

The final output is an automated Excel report containing KPI, branch, channel, and product-level analysis.

---

## 🎯 Business Objective

The main objective of this project is to analyze the home loan lifecycle from application to sanction and recovery.

The analysis focuses on:

- Loan application trends
- Sanction performance
- Applied vs sanctioned loan amounts
- Branch-level performance
- Channel performance
- Product performance
- Loan recovery
- Delinquency patterns
- Customer and loan-level insights

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Excel
- Jupyter Notebook
- OpenPyXL

---

## 📂 Dataset Structure

The original dataset contains multiple related sheets:

| Sheet | Purpose |
|---|---|
| Customer | Customer and loan application information |
| Channel | Channel lookup information |
| Product | Product lookup information |
| Branch | Branch details |
| Sanction | Sanctioned and disbursed loan information |
| Recovery | Recovery and delinquency information |

The raw dataset is not included in this repository to avoid exposing customer-level information.

---

## 🔄 Project Workflow

```text
Raw Excel Data
      ↓
Load Multiple Sheets
      ↓
Data Understanding
      ↓
Data Cleaning
      ↓
Data Validation
      ↓
Data Integration
      ↓
Feature Engineering
      ↓
Exploratory Data Analysis
      ↓
Business Analysis
      ↓
Visualization
      ↓
Automated Excel Report
