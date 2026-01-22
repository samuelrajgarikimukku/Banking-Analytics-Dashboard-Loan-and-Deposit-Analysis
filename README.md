# Banking-Analytics-Dashboard-Loan-and-Deposit-Analysis
This repository contains a multi-page Banking Analytics Dashboard built to analyze loans, deposits, and customer segments in a structured and reproducible way. The project focuses on presenting core banking metrics with clear segmentation and consistent filtering to support analytical and business-level decision making.

## Project Overview

The dashboard provides a consolidated analytical view of a bank’s financial position and customer distribution. It is organized into three main analytical sections: Home, Loan Analysis, and Deposit Analysis. Each section is designed to answer a specific class of business questions while sharing a common data model and filter logic.

The primary objective of this project is to demonstrate practical experience in financial analytics, dashboard design, and interactive reporting using real-world banking metrics.

## Dashboard Structure and Screenshots
1. Home – Executive Summary \
**Purpose**\
The Home page serves as a high-level snapshot for quick review. It summarizes overall banking performance and customer volume.

**Key Metrics Displayed**
- Total Clients: 3000
- Total Loan Amount: 4.38bn
- Total Deposit Amount: 3.77bn
- Business Lending: 2.60bn
- Checking Account Amount: 963.28M
- Savings Account Amount: 698.73M
**Filters Available**
  - Joining Year
  - Gender

<img width="927" height="519" alt="image" src="https://github.com/user-attachments/assets/b18aa964-d367-44bc-b230-3f968460a038" />


2. Loan Analysis\
**Purpose**\
This section provides a detailed breakdown of loan-related metrics and customer loan behavior across different segments.

**Key Metrics Displayed**
- Total Loan: 4.38bn
- Bank Loan: 1.77bn
- Business Lending: 2.60bn
- Credit Card Balance: 9.53M

**Analytical Breakdowns**
- Loan distribution by Banking Relationship
- Loan distribution by Occupation
- Loan distribution by Nationality
- Loan distribution by Income Band

**Filters Available**
- Joining Year
- Gender
- Banking Relationship
- Institution Advisor

<img width="917" height="511" alt="image" src="https://github.com/user-attachments/assets/50ddfbb7-a9d6-447c-a177-639eea0ffef1" />


3. Deposit Analysis

**Purpose**\
This section focuses on deposit behavior and account balances, using the same segmentation logic as the loan analysis for consistency.

**Key Metrics Displayed**
- Total Deposit: 3.77bn
- Bank Deposit: 2.01bn
- Savings Account Amount: 698.73M
- Checking Account Amount: 963.28M

**Analytical Breakdowns**
- Deposit distribution by Banking Relationship
- Deposit distribution by Occupation
- Deposit distribution by Nationality
- Deposit distribution by Income Band

**Filters Available**
- Joining Year
- Gender
- Banking Relationship
- Institution Advisor

<img width="929" height="512" alt="image" src="https://github.com/user-attachments/assets/f2170c51-913b-4e8e-a7da-073bb5d02f86" />

## Tools and Technologies Used 
- Power BI for data modeling, DAX measures, and interactive visualizations
- Structured data preparation and validation prior to reporting
- KPI cards, bar charts, and donut charts for financial and segmentation analysis

## Repository Structure

Suggested folder structure for clarity and maintenance:
```
Banking-Analytics-Dashboard/
│
├── screenshots/
│   ├── home_dashboard.png
│   ├── loan_analysis.png
│   └── deposit_analysis.png
│
├── dashboard/
│   └── Banking_Analytics_Dashboard.pbix
│
├── data/
│   └── source_data_files
│
└── README.md
```
## Professional Relevance

This project demonstrates the ability to design end-to-end analytical dashboards for financial data, apply consistent segmentation logic across multiple analytical views, and present complex metrics in a format suitable for both executive summaries and detailed analysis.

It reflects practical experience in banking analytics, customer segmentation, and decision-support reporting using industry-standard tools.
