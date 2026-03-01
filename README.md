# Revenue Quality & Discount Profitability Analysis  
**(Excel-Based E-Commerce Sales Intelligence)**

This project delivers a strategic profitability and revenue quality analysis of an e-commerce dataset (2014–2017) using advanced Microsoft Excel modelling techniques.

The objective was not just to report sales, but to diagnose how discounting behaviour impacts margin performance, identify revenue leakage, and provide executive-level recommendations for pricing governance and sustainable profit growth.

All analysis, modelling, KPI frameworks, and dashboards were built entirely in **Microsoft Excel**, demonstrating how Excel can be leveraged as a powerful business intelligence and decision-support tool.
## Project Objectives

- Analyse the impact of discount levels on profit margins
- Identify loss-making pricing patterns
- Quantify profit leakage caused by aggressive discounting
- Evaluate profitability across:
  - Customer segments
  - Product categories
  - Regions
  - Shipping modes
- Design executive KPIs to monitor discount risk
- Provide strategic recommendations to improve revenue quality

## Dataset Overview

- **Source**: E-Commerce transactional dataset (inspired by Kaggle).
- **Time Period**: 2014 – 2017
- **Grain**: Order Line Level

**Key Features**  
Order ID, Order Date / Ship Date, Customer ID / Segment, Region / State / City, Category / Sub-Category / Product Name, Sales, Quantity, Discount, Profit

**Engineered Fields**  
- Profit Margin  
- Order Month  
- Order Year  
- Quarter  
- Discount Status

## Data Cleaning & Preparation (Excel)

Before analysis, the dataset was transformed into a structured analytical model.

1. **Data Type Standardisation**  
   Converted Order Date and Ship Date from text to proper date format  
   Standardised numeric fields (Sales, Profit, Discount, Quantity)  
   Ensured consistent decimal precision

2. **Text Cleaning**  
   Removed extra spaces using TRIM  
   Standardised category and segment naming conventions  
   Ensured consistent state and region formatting

3. **Missing & Anomaly Checks**  
   Validated negative profit entries  
   Checked for blank customer IDs or product IDs  
   Flagged extreme discount levels for investigation

4. **Feature Engineering**  
   Created analytical columns:  
   - Profit Margin = Profit / Sales  
   - Discount Status = IF(Discount>0,"Discount","No Discount")  
   - Month Name, Month Number, Quarter, Order Year  

These engineered fields enabled profitability segmentation and time-based analysis.

## Methodology

1. **Exploratory Data Analysis (EDA)**  
   Using Pivot Tables, dynamic charts, and structured calculations:  
   - Sales & profit trend (2014–2017)  
   - Discount vs Profit Margin analysis  
   - Category-level profitability breakdown  
   - Region-level performance analysis  
   - Segment profitability comparison

2. **Profitability Decomposition**  
   Sales segmented by discount bands:  
   - 0 (No Discount)  
   - 0.1 – 0.2  
   - 0.3 – 0.5  
   - 0.6+  

   Revealed:  
   - 0–0.2 discounts generated majority of profit  
   - Discounts ≥0.3 consistently reduced margin  
   - High discounts (0.6–0.8) produced negative margins

3. **KPI Framework Design**  
   Designed executive-level KPIs within Excel dashboard:  

   **Core KPIs**  
   - Total Sales  
   - Total Profit  
   - Gross Profit Margin %  
   - Discounted Sales Ratio %  
   - Profit Leakage from Discounting  

   **Strategic KPIs**  
   - Profit by Category  
   - Profit by Region  
   - Profit by Customer Segment  
   - High-Risk Discount Rate (% of transactions with margin <0)

## Key Findings

1. **Profit is Concentrated in Low-Discount Sales**  
   Sales with discounts between 0%–20% generated the majority of net profit.

2. **Aggressive Discounting Destroys Value**  
   Discount levels ≥30% consistently led to:  
   - Margin compression  
   - Negative contribution  
   - Revenue growth without profit growth

3. **Revenue Growth ≠ Profit Growth**  
   High-volume discounted transactions increased sales but reduced overall margin.

4. **Category & Segment Imbalance**  
   Certain categories (e.g., Technology with high discounting) showed volatile margins compared to more stable categories like Office Supplies.

## Dashboard Design (Excel)

The final Excel dashboard includes:

- **Executive Summary Panel**  
  Total Revenue, Total Profit, Gross Margin %, Discounted Sales %, Profit Leakage

- **Profit Drivers**  
  Profit by Category (Bar Chart), Profit by Segment, Profit by Region

- **Risk Monitoring**  
  Discount vs Margin Scatter Plot, Monthly Margin Trend, High-Risk Discount Alert Indicator

All visuals powered by Pivot Tables and slicers for dynamic filtering.

## Strategic Recommendations

- Cap standard discounts at ≤20%
- Require approval for discounts ≥30%
- Align sales incentives with profit margin, not revenue volume
- Review pricing strategy for high-discount categories
- Monitor profit leakage monthly through structured KPIs

## Tech Stack

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Advanced Formulas
- Conditional Formatting
- Structured Tables
- Data Validation
- Dashboard Design

## Deliverables

- Cleaned & structured Excel dataset
- Pivot-based profitability model
- Executive dashboard
- Strategic recommendation framework

## Business Impact

This analysis demonstrates that:  

The company does not have a revenue problem — it has a **pricing governance problem**.

By tightening discount discipline, profit could increase significantly **without increasing sales volume**.

This project showcases:  
- Strong commercial thinking  
- Revenue quality analysis  
- Strategic KPI design  
- Executive communication capability  
- Advanced Excel modelling skills
---
