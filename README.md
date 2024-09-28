# Project Background

GONG Inc. is a fictional e-commerce company that specializes in selling office supplies online. GONG Inc. has accumulated substantial data across its sales, product offerings, discounts, and customer demographics. The objective of this project is to analyze that data to uncover insights that will help improve commercial success.

This project applies end-to-end data analytics process, from extracting data to building an interactive dashboard for tracking KPIs.

The tools and methods used include:

-	SQL for extracting datasets from relational database (PostgreSQL)
-	Power BI for building the data model, conducting exploratory data analysis, and creating an interactive dashboard
-	DAX functions for generating key metrics and calculations
-	Statistical methods for forecasting and analyzing trends, product performance, customer behavior, and order fulfillment

# Data Structure and Initial Check

The data used in this project, as pictured below, comes from four primary tables with a total row count of 8,001 records.

1.	Customer Table: Includes customer ID, age, state, region, and segment. Customers from Utah and Nebraska were excluded from the analysis.
2.	Sales Table: Contains transaction data for orders made between 2015 and 2017, including order details, discounts, and sales amounts.
3.	Products Table: Contains product information including product ID, category, subcategory, and price.
4.	Date Table: Contains information ordered by dates.

![Screenshot 2024-09-26 180842](https://github.com/user-attachments/assets/962ab7e8-6239-4a4c-9d12-eb51b1da6201)

Prior to the beginning of the analysis, a variety of quality checks were conducted including
- Data Cleaning: Ensuring no missing or inconsistent data for key metrics such as sales values and product IDs.
-	Data Filtering: Excluding customers from Utah and Nebraska and orders made outside the 2015 – 2017 period.
-	Data Integrity: Verifying relationships between tables, ensuring proper joins for analysis.

The SQL queries used to inspect and perform quality checks can be found [here](https://drive.google.com/file/d/1hQtSNpb3aFOoCCapTECQPRIj2y9dg4MF/view?usp=sharing).

# Executive Summary

## Overview of Findings

Through the analysis, key insights were uncovered that highlight opportunities for GONG Inc. to increase profitability, improve product offerings and enhance customer satisfaction. Key performance indicators show a steady upward climb in revenue except for declines. This indicates peak seasons for sales and revenue. Insights also show that discounts have no significant effect on sales revenue.

Below is an overview page from the Power BI dashboard, which includes five views: Summary, Product Analysis, Customer Analysis, Order Analysis, and Sales Forecasting. The entire dashboard can be viewed [here](https://drive.google.com/file/d/1mCR53WXQ4MmXNyKUsoQI2xXOKsElrYkC/view?usp=sharing).

![Screenshot 2024-09-28 133218](https://github.com/user-attachments/assets/3c020b69-9cec-4650-917a-305978761734)

## Sales Trend


The analysis revealed seasonal sales trends, with noticeable peaks during back-to-school and year-end periods. January to February show major declines in sales revenue. Discounts had no significant impact on sales volume, particularly during promotional campaigns.

### Key Trends:

-	Top Sales Periods: The highest sales were recorded in Q4 of each year.
-	Impact of Discounts: Sales show no significant increase or decrease during discount campaigns.
-	Regional Sales: Sales were highest in the Western region, while the Southern Region recorded the least amount of sales.
-	Customer Trends: Highest revenue comes from customers in the Gen X category reaching approximately $2.7million, while Gen Z customers recorded approximately $1.5million
-	Yearly Trend: The data shows a steady increase in revenue on a yearly basis.

## Product Performance

The product performance analysis identified key products driving revenue and profitability for GONG Inc. Office chairs were the top sellers, while technology had the highest average order value. However, some product categories underperformed in terms of both sales and profitability, offering opportunities for optimization.

### Key Insights:

-	Top-Performing Products: Office Chairs, Desks, Technology (including phones, copiers, electronics etc.)
-	Underperforming Products: Fasteners and office supplies such as envelopes and labels.

## Recommendations

Based on the findings, the following recommendations were made to help GONG Inc. improve its overall commercial performance:

1.	Marketing Campaigns: Partnership with the marketing team to make efforts in improving sales within the Gen Z category of customers
2.	Optimize Discount Strategy: Perform A/B testing to determine if an increase or decrease in discount rates would increase customer orders, subsequently increasing revenue especially during peak sales periods.
3.	Product Line Adjustment: Increase visibility on underperforming product categories, while continuing to promote high-margin products.
4.	Root-Cause Analysis: Investigate further the reason behind sales dip in non-peak performing periods and determine if there might be ways to mitigate this.
