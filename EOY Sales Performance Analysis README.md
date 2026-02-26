EOY SALES PERFORMANCE ANALYSIS
Table of Contents

#problem-statement
#data-overview
#tools-used
#data-description
#data-cleaning--preparation
#analysis-performed
#visualizations
#key-insights
#recommendations--bi-questions


Problem Statement
The aim of this analysis is to observe sales performance trends across the months of the year with a focus on key revenue‑driving KPIs such as customer relations, brand performance by field sales reps (FSMs), return rates, and monthly revenue/ASP variances across brands.

Data Overview
The dataset was extracted from the Jin Li Supply Chain Management (JL SCM) software used by 3CHub Brand Management Ltd to record daily sales, customer transactions, device movements, and brand‑level activities.

Tools Used

Excel
SQL
Jin Li SCM


Data Description
The dataset includes:

SKU‑level transaction logs
Daily and monthly unit sales
Revenue and discount records
Return logs
Brand performance metrics
Field Sales Manager (FSM) performance
Customer transaction metadata
ASP (Average Selling Price) records
Payment and invoice details


Data Cleaning & Preparation
Data was cleaned and transformed using:

Removal of duplicates
Cell formatting and column standardization
Power Query for merging brand, SKU, and transaction tables
Power Pivot for data modelling
DAX measures for KPIs (ASP, variance, YoY/MoM changes)
Excel dashboarding for storytelling and visual interpretation


Analysis Performed

Monthly sales trend analysis
Revenue and ASP variance analysis
Brand‑level and FSM performance breakdown
Demand forecasting
Return rate comparisons
Contribution analysis by brand and model
Discount distribution analysis
MoM trend evaluation


Visualizations

Bar charts
Line graphs
Pie charts
Pivot tables
Excel dashboards (interactive)

(Add your images like this once uploaded)
Markdown../images/EOY_dashboard.pngShow more lines

Key Insights

Demand peaks in December (₦110.3m revenue from 838 units), indicating strong year‑end seasonality and promotional impact.
Brand concentration is high — TECNO + INFINIX account for ~58.5% of net sales and ~55.3% of units.
Entry and mid‑tier smartphones dominate volume; the top 6 models contribute a major share of total revenue.
Return rate is low (~1%), with higher rates concentrated in OPPO, VIVO, and Samsung (low transaction base).
Discounting is moderate (median ~5%), with most transactions falling within the 0–10% discount range (excluding placeholder prices).


Recommendations / BI Questions

Which promotions or price changes caused the December spike? Can they be applied earlier (Sept–Nov) to smooth demand?
Is the current brand mix (TECNO/INFINIX/ITEL/XIAOMI) aligned with margins and inventory turns?
What is the proper baseline list price for discount measurement? Placeholder DISPLAY prices distort discount rates.
Are returns correlated with specific models, batches, or FSM promoters?
Identify bulk buyers/resellers via customer phone patterns and consider a B2B pricing tier.
Confirm whether Own Sample transactions are excluded from KPIs and properly tracked.
How accurately does payment method mix reflect customer behavior? JL often logs only Cash Sale.
Are discrepancies present between Actual Amount vs Sale Amount Without Tax and VAT recording?
