# **EOY SALES PERFORMANCE ANALYSIS**

---

## **Table of Contents**
- [Problem Statement](#problem-statement)
- [Analysis Overview](#analysis-overview)
- [Data Source](#data-source)
- [Preparation Tools](#preparation-tools)
- [Data Processing](#data-processing)
- [Skills Demonstrated](#skills-demonstrated)
- [Objective](#objective)
- [Key Insights](#key-insights)
- [Recommendations / BI Questions](#recommendations--bi-questions)
- #dashboard
- #conclusion
- [Dashboard Interaction](#dashboard-interaction)

---

## **Problem Statement**
This analysis evaluates end‑of‑year (EOY) sales performance to uncover monthly trends, key revenue drivers, brand strength, customer behavior patterns, return rates, discount dynamics, and ASP (Average Selling Price) variance across all brands.

The goal is to generate actionable insights that support better commercial decision-making and future planning.

---

## **Analysis Overview**
This project includes multi‑level analysis covering:

- Monthly revenue and unit trends  
- Seasonality and demand spikes  
- Brand-level and model-level performance  
- Field Sales Manager (FSM) effectiveness  
- Return rates and potential root causes  
- Discounting behavior and pricing inconsistencies  
- Customer interaction and repeat purchase signals  
- MoM variance analysis  
- Demand estimation using historical patterns  

---

## **Data Source**
Data was sourced from the **Jin Li Supply Chain Management (JL SCM)** software used by **3CHub Brand Management Limited**.

JL SCM provides:

- Transaction logs  
- SKU/brand/model metadata  
- Customer and invoice details  
- Discount records  
- Return/swap logs  
- Pricing and payment method data  
- Daily/monthly operational data  

---

## **Preparation Tools**
- **Microsoft Excel**  
- **SQL**  
- **Jin Li SCM**  
- Power Query  
- Power Pivot  
- DAX for KPI computation  

---

## **Data Processing**
Data cleaning and transformation steps included:

- Removing duplicates  
- Cleaning placeholder "LIVE DISPLAY" prices  
- Formatting date, revenue, discount, and ASP fields  
- Merging multiple tables using **Power Query**  
- Building a structured model using **Power Pivot**  
- Creating DAX measures for:  
  - ASP  
  - Discount %  
  - Contribution %  
  - MoM Variance  
  - Return Ratio  
  - Revenue KPIs  
- Developing an interactive Excel dashboard  

You may include processing screenshots here:

```markdown
![Data Processing Snapshot](../images/data_processing_example.png)
