# Quickmart Superstore Sales Analysis

## 📊 Project Overview
Analyzed 1,000 sales transactions ($322,967 revenue) for a superstore chain with 3 branches across 3 cities (Yangon, Mandalay, Naypyitaw) to identify revenue drivers, product performance, and customer behavior.

## ❓ Business Problem
Management wanted to know:
1. Which city/branch/product line drives the most revenue?
2. What is the true profitability after fixing data errors?
3. How do customer types and payment methods affect sales?

## 📁 Dataset
- **Source:** Supermarket Sales Dataset (3 months: Jan-Mar 2019)
- **Rows:** 1,000 Invoices
- **Columns:** Invoice ID, Branch, City, Customer Type, Gender, Product Line, Unit Price, Quantity, Tax 5%, Total, Date, Time, Payment, COGS, Gross Income, Rating

## 🧹 Data Cleaning (Advanced Excel)
Performed in `Quickmart Superstore Clean Data.xlsx`:

1.  **Removed illogical aggregation:** Deleted `Sum of Unit Price` - summing unit prices has no business meaning
2.  **Fixed Gross Margin % Error:** Original formula showed 476.19%. Fixed to correct business logic:
    `Gross Margin % = Gross Income / Total = 4.7619%`
3.  **Validated Business Logic:** Confirmed `Tax 5% = Gross Income` (COGS * 5%) - standard for this retailer
4.  **Created Time Dimensions:** Extracted Month, Year from Date for trend analysis
5.  **Data Type Fixes:** Formatted Date, Currency, Percentage columns

## 📈 Key Metrics (KPIs)
- **Total Orders:** 1,000
- **Total Quantity:** 5,510
- **Total Revenue:** $322,967
- **Total COGS:** $307,587
- **Total Tax / Gross Income:** $15,379
- **Profit Margin:** 4.76%

## 💡 Key Insights

- **Location:** Naypyitaw is top city ($110,569) despite Mandalay having more transactions. Indicates higher basket size.
- **Product:** Food and beverages is top revenue driver ($56,145), while Health and Beauty is lowest ($49,194)
- **Customer:** Members = $164,223 (50.8%) vs Normal = $158,743 - Loyalty program is effective
- **Seasonality:** January was peak month ($116,292) vs February ($97,219) - 19.6% growth
- **Payment:** Cash ($112,207) and Ewallet ($109,993) dominate over Credit Card ($100,767)

## 🛠️ Tools Used
- **Excel:** Data cleaning, PivotTables, Formulas, Data Validation
- **Excel Dashboard:** Interactive Slicers (Gender, Branch, City), Bar/Donut/Column charts

## 📸 Dashboard
![Dashboard](Quickmart%20superstore%20Dashboard.png)

## 📂 Files in this Repo
- `Quickmart superstore Raw Data.csv` - Original raw dataset
- `Quickmart Superstore Clean Data.xlsx` - Cleaned & transformed data with correct margin %
- `Quickmart superstore Dashboard.png` - Final interactive dashboard


## 👤 Author
Ayodeji Orikogbo Data Analyst | Open to Retail / Ecommerce Analyst roles in UK
LinkedIn: www.linkedin.com/in/ayodejiorikogbo
