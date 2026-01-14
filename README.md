# Amazon-Sales-Performance-Analysis
An end-to-end analysis of sales trends and revenue leakage using Excel and Power BI

Amazon Sales Performance & Revenue Leakage Analysis (2025)

Executive Summary:

This project analyzes Amazon's sales performance for the first few months of 2025, uncovering a substantial gap between gross demand and realized returns.
While the business yielded $244K in Gross Revenue, it suffered a $155K revenue loss driven by a weak overall order completion rate of 35%. 
The analysis identifies specific payment method failures and geographic bottlenecks as the primary drivers of lost sales.

Business Problem:

The main challenge is a critically low completion rate ($35%). Despite high market appeal and a strong Average Order Value ($975),
the business is unable to translate customer interest into complete transactions. 
This signals technical issues in the checkout process or regional performance issues rather than a lack of market demand.

Methodology:

Dataset acquired from Kaggle (Amazon Sales Performance 2025).
Imported raw CSV data into Microsoft Excel.
Used Power Query for data cleaning.
Imported cleaned data into Power BI for data modeling and visualization.
 

Skills:

Excel: Data Cleaning & ETL (Power Query)
Power BI: DAX, ETL, data modelling, data visualization
Statistical Analysis:  SVI, Distribution of Price


Results & Insights:

Product Performance: Electronics and Home Appliances are the primary revenue drivers, contributing 85% of total revenue.
Payment Issues: Gift Cards have the lowest completion rate at 14%, followed by Credit Cards at 31%. These are the core drivers of the $155K revenue leakage.
Geographic Issues: San Francisco generates the most sales volume ($42K) but loses the most revenue ($29K) due to a 33% completion rate.
                       Boston is the lowest performing major market with only a 12% completion rate.
Customer Base: The high Average Order Value ($975) suggests a high-value customer segment that justifies investment in smoother and stable fulfillment processes.

Business Recommendations:

Resolve Payment Issues: Perform a technical audit of the Gift Card and Credit Card processing systems, since they are the core drivers of unfulfilled orders.
Regional Optimization: Evaluate order fulfillment in Boston and San Francisco to identify obstacles that may be driving failed orders.
Customer Retention: Implement approaches like automated email sequence,  particularly for high-value orders that failed to complete.

Next Steps:

Perform a Root Cause Analysis on the "Cancelled" vs. "Pending" orders to see if they are system-initiated or user-initiated
Transition the data into a SQL database to perform complex joins with "Customer Feedback" tables for sentiment analysis.
