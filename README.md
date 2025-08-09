# Bank Loan Analysis (Excel) — Interactive Dashboard

> Excel-native analytics that tracks lending KPIs, separates **Good vs Bad loans**, and surfaces trends by **time, region, purpose, employment length, and home ownership**.

[![Made with Excel](https://img.shields.io/badge/Made%20with-Excel-217346.svg)](#)  

---

## Table of Contents
- [Overview](#overview)
- [Business Questions](#business-questions)
- [Key KPIs](#key-kpis)
- [Dashboards](#dashboards)
- [Data Dictionary](#data-dictionary)
- [How to Use (GitHub Pages + Excel Embed)](#how-to-use-github-pages--excel-embed)
- [Formulas & Time Intelligence](#formulas--time-intelligence)
- [Repository Structure](#repository-structure)
- [Screenshots](#screenshots)
- [Results & Insights](#results--insights)
- [Improvements & Next Steps](#improvements--next-steps)
- [Tech / Skills](#tech--skills)
- [License](#license)
- [Contact](#contact)

---

## Overview
This project is a **Bank Loan Reporting System** built entirely in **Excel** (PivotTables/Charts, Slicers & Timelines, Power Query, and the Data Model/Power Pivot).  
It helps a bank:
- **Monitor** lending activity and repayments with **MTD**/**MoM** comparisons
- **Assess risk** by separating **Good loans** (Fully Paid/Current) and **Bad loans** (Charged Off)
- **Analyze trends** by month, region (state), loan term, employment length, purpose, and home ownership

---

## Business Questions
1. How many **loan applications** are we receiving over time (overall, MTD, MoM)?
2. What is the **total funded amount** and **total amount received** (overall, MTD, MoM)?
3. What is the **average interest rate** and **average DTI** trends?
4. What portion of our portfolio is **Good** vs **Bad**, and how does that affect cash flow?
5. Which **states**, **loan purposes**, **terms**, **employment lengths**, and **home ownership statuses** are most associated with higher funding and better repayment?

---

## Key KPIs
- **Total Loan Applications**
- **Total Funded Amount**
- **Total Amount Received**
- **Average Interest Rate**
- **Average DTI (Debt-to-Income)**
- **Good Loan KPIs** (Fully Paid, Current):  
  - Good Applications, Good Funded Amount, Good Received Amount, Good %
- **Bad Loan KPIs** (Charged Off):  
  - Bad Applications, Bad Funded Amount, Bad Received Amount, Bad %

Each KPI supports **MTD** and **MoM** deltas.

---

## Dashboards

### 1) Summary Dashboard
- KPI cards: Applications, Funded Amount, Amount Received, Avg Interest, Avg DTI  
- **Good vs Bad** split with dedicated KPIs  
- MTD and MoM indicators

### 2) Overview Dashboard
- **Monthly Trends** (line): applications, funded, received  
- **Regional Analysis** (filled map): by state  
- **Loan Term** (donut): 36 vs 60 months  
- **Employment Length** (bar)  
- **Loan Purpose** (bar)  
- **Home Ownership** (treemap)

---

## Data Dictionary
Core fields used (abridged):
- **Loan ID** – unique loan identifier  
- **Issue Date** – loan origination date  
- **Loan Status** – Current, Fully Paid, Charged Off  
- **Loan Amount** – principal funded  
- **Interest Rate** – annual rate  
- **Instalment** – monthly payment amount  
- **DTI** – debt-to-income ratio  
- **Purpose** – e.g., debt consolidation, credit card  
- **Grade / Sub-Grade** – risk category  
- **Address State** – borrower state  
- **Employment Length / Title** – job stability and role  
- **Home Ownership** – own, rent, mortgage  
- **Last Payment / Next Payment Date** – repayment tracking

---
##  Deliverables

-  **[Interactive Excel Dashboard (View on Excel Web)](https://1drv.ms/x/c/a2cba49479d148f3/ETWtSQwuQChFs4rJM56aCMABraCdfbSnNFGmVqkXXv_7jQ?e=LTYubV)**  
-  Project documentation (This Repo)

---

## Results & Insights
- Clear visualization of **application volume** and **cash flow** (funded vs received).  
- **Risk overview** via Good vs Bad cohorts with concrete KPIs.  
- **Regional hotspots** identified for targeted marketing and credit policy tuning.  
- **Borrower profile segments** (purpose, term, employment length, home ownership) tied to portfolio performance.

---

## Improvements & Next Steps
- **Predictive default risk** (classification model) using borrower attributes and payment history  
- **Automated refresh** via Power Query + scheduled OneDrive refresh  
- **Drill-through** views for borrower-level records  
- **Enhanced risk scoring** with external credit data  
- **Accessibility/UX**: high-contrast theme, descriptive labels, keyboard-friendly slicers

---

## Contact
**Taran Arora**  
- LinkedIn: [https://www.linkedin.com/in/taran--arora/](https://www.linkedin.com/in/taran--arora/)  
- Portfolio: [https://taranarora.github.io/TaranAroraDA.github.io/](https://taranarora.github.io/TaranAroraDA.github.io/)  
- GitHub: [https://github.com/TaranArora/My-Portfolio](https://github.com/TaranArora/My-Portfolio)

