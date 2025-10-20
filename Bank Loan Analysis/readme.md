
<h1 align="center">🏦 Bank Loan Analysis Project</h1>

<p align="center">
  <em>Data-driven insights into loan performance, funding trends, and borrower behavior</em>
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.9+-3776AB?logo=python&logoColor=white">
  <img alt="Pandas" src="https://img.shields.io/badge/Pandas-EDA%20%26%20Data%20Wrangling-150458?logo=pandas">
  <img alt="Matplotlib" src="https://img.shields.io/badge/Matplotlib-Data%20Visualization-FC4C02?logo=plotly">
</p>

---

## 🧭 Overview

This project performs an in-depth **bank loan data analysis** using Python.  
The analysis explores **loan disbursement patterns**, **repayment behavior**, **default ratios**, and **key financial indicators** such as **funded amounts**, **interest rates**, and **DTI (Debt-to-Income)** ratios.  

By visualizing trends and metrics, we gain valuable insights into **loan performance**, **customer reliability**, and **regional lending trends** — essential for financial risk assessment and strategic decision-making.

---

## 🧮 Tools & Libraries Used

| Category | Tools |
|-----------|-------|
| Data Handling | `pandas`, `numpy` |
| Visualization | `matplotlib`, `seaborn`, `plotly.express` |
| Environment | Jupyter Notebook |
| Data Source | `financial_loan.xlsx` |

---

## 🧾 Dataset Description

**File:** `financial_loan.xlsx`  
**Records:** 38,576 rows × 24 columns  
**Key Fields:**
- `loan_amount` – Approved loan amount  
- `total_payment` – Total amount received  
- `int_rate` – Interest rate per loan  
- `dti` – Debt-to-income ratio  
- `emp_length` – Employment length  
- `loan_status` – Loan repayment status (`Fully Paid`, `Current`, `Charged Off`)  
- `purpose`, `address_state`, `term`, `grade`, `issue_date`

---

## 📊 Key Analyses & Results

### 🔹 Total Loan Applications
- **Total Applications:** 38,576  
- **MTD Applications:** 4,314  

### 🔹 Total Funded Amount
- **Overall Funded:** \$435.76M  
- **Month-to-Date Funded:** \$53.98M  

### 🔹 Total Amount Received
- **Total Payments Received:** \$473.07M  
- **Month-to-Date Payments Received:** \$58.07M  
> 💡 The total payments exceed total funded amounts — a **positive financial indicator** for the bank.

### 🔹 Average Financial Metrics
| Metric | Value |
|--------|--------|
| **Average Interest Rate** | 12.05% |
| **Average DTI Ratio** | 13.33% |

---

## 💰 Loan Performance Insights

| Category | Percentage | Total Amount |
|-----------|-------------|----------------|
| ✅ **Good Loans (Fully Paid / Current)** | 86.18% | \$370.22M |
| ❌ **Bad Loans (Charged Off)** | 13.82% | \$65.53M |

> The high ratio of good loans (86%) indicates strong lending performance and reliable borrowers.

---

## 📈 Visual Analyses

### 1️⃣ Monthly Trends
- **Funded Amount by Month**
- **Received Amount by Month**
- **Loan Applications by Month**

These plots reveal seasonal patterns in lending activity and repayments.

### 2️⃣ Regional Distribution
- **Total Funded Amount by State (in \$ Thousands)**
  - States like **CA, NY, and TX** show the highest loan volumes.

### 3️⃣ Loan Term Distribution
- **36 months vs 60 months** comparison  
  - 60-month loans contribute a higher share of the total funded amount.

### 4️⃣ Employment Length
- Analysis of how **job stability (employment length)** affects total loan amounts.

### 5️⃣ Loan Purpose
- **Top loan purposes** (e.g., debt consolidation, credit card, home improvement) dominate the total funding landscape.

---


## 🔍 Insights Summary

- 📈 **Positive cash inflow:** Total received > Total funded.  
- 🏦 **Healthy portfolio:** 86% of loans are current or fully paid.  
- 📉 **Default control:** Bad loans under 14%.  
- 💵 **Higher funding in long-term loans** (60 months).  
- 🌎 **Regional concentration:** Loans are largely distributed across a few high-income states.  

---
