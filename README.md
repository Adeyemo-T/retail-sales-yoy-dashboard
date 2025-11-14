# Store Sales Performance: Year-over-Year (YOY) Analysis 2023 vs 2024

##  Project Background

A retail client requires a direct comparative analysis to measure the growth, profitability, and operational efficiency between the current year (2024) and the prior year (2023). The primary goal is to determine the effectiveness of strategic changes by quantifying the **Year-over-Year (YOY)** variance across all critical performance indicators.

This project delivers a focused dashboard that highlights growth drivers, cost control success, and product sales shifts between the two fiscal periods.

Insights and recommendations are provided on the following key areas:
* **YOY Growth and Profitability:** Quantifying the percentage change in **Sales (30% vs LY), Profit, Cost (11% vs LY), and Quantity (24% vs LY)** versus the prior year.
* **Monthly Volatility:** Detailed tracking of the **Monthly Revenue Trend** to pinpoint exactly when growth or decline occurred.
* **Regional Performance:** Benchmarking sales performance across different geographical regions (West, South, North, East).
* **Product Line Shifts:** Identifying which specific product categories are contributing the most to the YOY change.

***

### 🔗 Technical Deliverables

* **Interactive Dashboard:** The full Store Sales Performance dashboard can be accessed [here](LINK_TO_POWER_BI_DASHBOARD).
* **Time Intelligence Focus:** The project features advanced DAX (Data Analysis Expressions) or Excel Calculated Measures for complex **Year-over-Year (YOY)** calculations and trend comparisons.

##  Data Structure & Initial Checks

### 📊 Data Overview
The analysis was built entirely within a **single Excel workbook**, demonstrating expertise in leveraging Excel's advanced data handling capabilities for complex comparative analysis. All raw transactional data was loaded into an Excel **Data Table**.

#### Data Model (Implicit Star Schema)
The structure utilizes an **implicit Star Schema** model within Excel's framework:

* **Central Table:** The primary Data Table (containing fields for Sales, Profit, Cost, Quantity, Region, Product, and Date) acts as the central **Fact Table**.
* **Time Dimension:** The **Date field** allows for the creation of calculated columns to derive the necessary time attributes (Year, Month) required for advanced YOY comparison.

### Data Cleaning and Preparation
The data cleaning and preparation process utilized native Excel tools, Pivot Tables, and **Calculated Measures** to derive the core dashboard insights.

* **Time Intelligence (Calculated Measures):** All core KPIs, including **30% VS LY Sales**, **24% VS LY Quantity**, and **11% VS LY Cost**, were derived using **Calculated Measures** within Excel (or a helper table).
* **Aggregation:** **Pivot Tables** were used to efficiently summarize the transactional data set into the visible components of the dashboard, such as the **Regional Sales Distribution** and the **Monthly Revenue Trend**.

## Executive Summary (Store Sales Performance)

The business is experiencing explosive growth, with **Sales up 30%** and **Quantity up 24%** versus the last year (LY). Total **Sales reached $475.6K** and **Profit hit $411.6K**. However, the efficiency of this growth is challenged by a **11% increase in Cost VS LY**, suggesting procurement or operational expenses are rising too quickly. The growth is geographically unbalanced, relying heavily on the **West and South regions**. Strategic focus must immediately pivot to controlling the cost growth rate and replicating the success of the high-growth **Monitor and Mouse** categories in other regions.

***

### 1. YOY Growth and Financial Efficiency

* **Strong Revenue Growth:** **Sales are up 30%** and **Quantity is up 24%**.
* **Profitability Risk:** The **11% increase in Cost VS LY** is outpacing the Quantity growth, indicating the efficiency of sales is declining.
* **Monthly Volatility:** The Monthly Revenue Trend shows that **2024 is outperforming 2023** in most months, confirming that the growth is sustained, though monthly variance remains high.

![YOY Performance KPIs and Monthly Trend]

***

### 2. Regional Sales Distribution

* **Regional Reliance:** The **West and South regions** are the primary drivers of YOY growth, confirming that these areas contain the most optimized sales and logistics processes.
* **Underperforming Regions:** The **North and East regions** are lagging, indicating a need for strategic intervention and resource allocation to replicate the West/South success model.

![Regional Sales Distribution Chart]

***

### 3. Product-Wise Breakdown

* **Growth Drivers:** The **Monitor** and **Mouse** product categories show the largest YOY sales increase, confirming they are the most effective product lines in the current market.
* **Stagnant Categories:** Categories like **Headphones** and **Keyboard** show less aggressive growth, suggesting the need for revised marketing or competitive pricing strategies to reignite sales.

![Product-wise Sales Breakdown Chart]

##  Business Recommendations

Based on the analysis of high YOY growth and emerging cost and regional disparities, the following five strategic actions are critical to sustaining profitable growth:

* **1. Immediately Investigate Cost Growth (11% VS LY):** Identify the root cause of the **11% Cost increase**. This may involve auditing procurement contracts, logistics expenses, or supply chain inefficiencies to align cost growth with or below Quantity growth (24% VS LY).
* **2. Replicate Regional Success Model:** Analyze the operational and sales strategies of the **West and South regions** and mandate their adoption in the underperforming North and East regions to balance the sales distribution.
* **3. Prioritize High-Growth Products:** Focus inventory stocking, marketing spend, and sales incentives on the **Monitor and Mouse** categories to maximize returns from the most effective product lines.
* **4. Relaunch Stagnant Categories:** Develop targeted promotional strategies or bundle deals for **Headphones and Keyboards** to boost their YOY sales performance and prevent them from becoming financial burdens.
* **5. Optimize Inventory Against Monthly Volatility:** Use the Monthly Revenue Trend to refine procurement timing, ensuring that inventory is fully stocked ahead of historical **peak months** and scaled back during known trough periods.

---

Thank you for reading! Leave a comment if you have any questions about the analysis.
