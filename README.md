# 🏦 Advanced Bank Loan Data Analysis — Power BI Dashboard

Empowering data-driven lending decisions through dynamic, interactive Power BI dashboards.

## 📌 Problem Statement

Traditional loan reporting methods fall short in providing a comprehensive view of lending operations, borrower behavior, and loan performance metrics. This project addresses that gap by building a suite of interconnected, interactive dashboards that deliver actionable insights across the full lending lifecycle.

## 🎯 Objective

To design a set of Power BI dashboards offering a holistic view of loan applications, funding, borrower demographics, and loan performance — enabling stakeholders to make faster, data-backed lending decisions.

## 📊 Dashboards

### 1. Executive Summary
High-level KPIs for evaluating overall lending performance, with Total (MTD) and Month-over-Month (MoM) trend tracking:
- **Total Loan Applications**
- **Total Funded Amount**
- **Total Amount Received**
- **Average Interest Rate**
- **Average Debt-to-Income Ratio (DTI)**
- Good vs. Bad Loan breakdown (applications, funded amount, received amount)
- Loan status table (Fully Paid, Charged Off, Current)

### 2. Overview
Visual breakdown of loan applications across multiple dimensions:
- Loan applications trend by month
- Applications by state (map visual)
- Applications by loan term (36 vs. 60 months)
- Applications by employee length
- Applications by loan purpose
- Applications by home ownership

### 3. Details
Granular, filterable loan-level table including ID, purpose, home ownership, grade/sub-grade, issued date, funded amount, interest rate, installment, and received amount.

All pages include interactive slicers for **State**, **Grade**, and **Good vs. Bad Loan** classification.

## 🧾 Key Metrics (Snapshot)

| Metric | Value |
|---|---|
| Total Loan Applications | 38.6K |
| Total Funded Amount | $435.8M |
| Total Amount Received | $473.1M |
| Average Interest Rate | 12.0% |
| Average DTI | 13.3% |
| Good Loan Issued | 86.2% |
| Bad Loan Issued | 13.8% |

## 🛠️ Tools & Technologies

- **Power BI Desktop** — data modeling, DAX measures, dashboard design
- **DAX** — for MTD, MoM, and derived KPI calculations
- **Data Cleaning & Transformation** — Power Query

## 📁 Repository Structure

```
├── data/                  # Source loan dataset
├── Bank_Loan_Report.pbix  # Power BI dashboard file
├── screenshots/           # Dashboard preview images
└── README.md
```

## 🖼️ Preview

> Add dashboard screenshots here (Summary, Overview, Details pages).

## 🚀 How to Use

1. Clone this repository
2. Open `Bank_Loan_Report.pbix` in Power BI Desktop
3. Use the slicers (State, Grade, Good vs. Bad Loan) to explore the data interactively

## 📈 Key Insights

- The majority of loans (86.2%) are classified as "Good Loans," reflecting healthy overall portfolio performance.
- Debt consolidation is the leading loan purpose, followed by credit card and other categories.
- 36-month terms account for the majority (73.2%) of loans issued.
- Loan applications show a consistent upward trend from January through December.

## 👤 Author

Feel free to connect for feedback or collaboration.

---
*This project was built as a hands-on exercise in Power BI dashboard design and lending data analytics.*
