# 🚚 US-Retailer-Supply-Chain-Sales-Performance-Analysis

## 1. Objective

This project focuses on analyzing the **supply chain operations** and **sales performance** of a retail business from January 2014 to April 2017 by using **Excel** and **Power BI**. The goal is to uncover operational inefficiencies, track sales performance metrics, and support data-driven decision-making.

## 2. Tools used

- Microsoft Excel: Used for data preparation and data mapping to prepare the necessary inputs for Power BI.  
- Power BI: Used for data visualization and interactive analysis to extract actionable insights.

## 3. Process

### Start with Excel (Data Preparation)

- Restructured the dataset.  
- Split the raw data into 7 dimension tables (customer, calendar, product, product category, product sub-category, sales region, shipping mode) and 1 fact table (sales).  
- Recheck the created tables if any errors still occur.  
- Ensured consistency and readiness for dynamic reporting.

### Proceed to Power BI (Data Visualization & Analysis)

- Cleaned and transformed raw data using Power Query.  
- Built a semantic model and used DAX to calculate necessary metrics (e.g. Total Profit, Growth rate, Performance To-Date, Previous Period, etc.)  
- Visualize the data and figure out meaningful insights.

## 4. Key findings:

### >> Summary:

- Sales show steady but modest growth, with a 12.03% average profit margin.  
- Total cost consumes 87.5% of revenue, could be due to excess inventory of low-profit items, high return rates, ineffective discounting, and delivery inefficiencies.  
- Long lead times suggest complex logistics operations or underperforming order processing time

### >> Page 1: Sales

- Revenue growth in 2017 lags behind 2016, especially in YoY monthly comparisons, warranting further investigation.  
- Consistent peak sales in Q3, Q4, aligning with major sales events, such as back-to-school season and year-end holiday shopping.  
- West and East regions lead in sales and profit, while Central and South underperform.  
- Central region’s over-discounting harms profit margin without increasing sales.  
- The Consumer segment drives over 50% of total revenue.  
- Phones and Chairs are top-selling sub-categories.

### >> Page 2: Supply chain

- Q3 and Q4 have peak order volumes yet maintain the fastest delivery times, indicating strong seasonal planning in exchange for higher inventory costs.  
- West has the highest return rate and costs; Anna is the sales representative with the highest return rate (11.7%), nearly 4x higher than peers.  
- Central suffers from the slowest deliveries (average 37 days); South has the lowest sales and orders.  
- Machines sub-category leads the quantity return rate at 13.9% → suggesting potential quality or unclear product instruction issues.  
- Customers tend to purchase orders at the start of the week or on weekends.  
- High return rate: 5.91% for order return rate and 8.06% for quantity return rate, suggesting issues related to product quality or fulfillment accuracy due to short lead time.  
- Return rate has increased in 2017, possibly signaling declining service or product quality. This requires further analysis.  
- An average lead time of 34.61 days and a 37.35% late delivery rate reflect significant supply chain inefficiencies.

### >> Page 3: Correlation

- Fast delivery equals high return rate (Same-Day Delivery has the highest return rate (7.2%)), indicating issues with delivery reliability, quality control issues at warehouse, lacking available products leading to back orders, or mismatch with customer expectation.  
- Technology and Furniture, while high-value, have elevated return rates (7.97% and 7.71% v). This could be due to any minor defects, compatibility issues, obsolescence risks, or unmet expectations.  
- West and East regions are high-cost, high-reward markets. They perform well in profit, but the high return rate could erode long-term gains or signal customer dissatisfaction. Meanwhile, Central region suffers from relatively high costs but lowest profits.  
- Furniture is slow-moving and bulky item, yielding lowest profit, posing obsolescence risk and high storage costs.

### >> Page 4: Forecast

- With 90% Confidence interval, Revenue is projected to grow but remain volatile.  
- Profit and customer base are expected to increase steadily.

## 5. Recommendations

### >> Sales

- **Discount Management**:  
    - Modify suitable discount rate at Central region to improve margins.  
    - Introduce different promotion packages, including product bundles, upselling and cross-selling, loyalty rewards to boost sales without negatively affecting profit margins.  
    - Target low-performing months (April, July) with strong promotional campaigns.

- **Product Focus**:  
    - Increase promotion campaigns for office supplies and technology products or expand the product lines to attract more new customers.  
    - Phase out slow-moving and low-margin SKUs to reduce warehousing costs.

- **Target tactics**:  
    - Push notifications and emails during peak shopping periods.  
    - Optimize customer support team during peak days.  
    - Reinvest in South region with localized promotions, logistics enhancements, and better inventory distribution.

### >> Supply chain

- **Return Rate**:  
    - Review sales skills or retrain sales reps (e.g. Anna)  
    - Enhance product quality checkups before delivery and post-purchase support.  
    - Improve product usage instructions, especially for Machines, Tables, and Appliances.  
    - Collect customer feedback on return reasons to identify root causes and plan corrective actions

- **Delivery Performance**:  
    - Adjust pricing for each shipping mode to balance customer expectation and cost.  
    - Focus on cost-effective Standard Class and Second Class shipping mode.  
    - Consolidate shipments to optimize delivery windows and reduce logistics costs.  
    - Allocate more resources and workforce at the start of the week and on weekends.

- **Inventory Management**:  
    - Increase stocks for high-demand categories like Technology and Office Supplies  
    - Tighten inventory control (e.g. ABC analysis) for slow-moving and low-profit products to avoid obsolete risk, reduce holding costs, and free up spaces in warehouse.  
    - Improve product quality and descriptions, particularly for Machines, Tables, and Appliances  
    - Improve demand forecasting to ensure product availability when needed.
