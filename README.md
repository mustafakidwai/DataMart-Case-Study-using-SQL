# Project: Data Mart Case Study  
![image](https://github.com/user-attachments/assets/45320bce-d558-4ec0-8d08-3fd47894cae2)

## Summary  

This project involved analyzing sales and performance data for Data Mart, a venture that shifted to sustainable packaging in June 2020. Using SQL, I cleansed and explored the dataset to draw meaningful insights. Key tasks included identifying missing data, calculating metrics like sales and transactions, and deriving insights based on demographic trends, platforms, and regions.
The focus was to generate actionable insights from the weekly_sales data while ensuring data quality through comprehensive cleansing techniques. Below is the breakdown of what was achieved through this project:

## Introduction
This project analyzes the sales performance of Data Mart following a shift to sustainable packaging. The aim was to explore sales trends across regions, demographics, and platforms, identifying potential gaps and patterns. The analysis was conducted using SQL to extract insights from the weekly_sales dataset.

## Project Highlights
#### Data Cleansing
Created a clean version of the weekly_sales table with:
 - Week number, month number, and calendar year columns derived from week_date.
 - New age_band and demographic columns based on segment mapping.
 - Null values replaced with 'Unknown' to maintain data integrity.
 - Generated a new avg_transaction column by dividing sales by transactions.

#### Key SQL Queries and Insights

1. Identifying Missing Weeks: Checked for missing week numbers to ensure data completeness.

2. Total Transactions by Year: Aggregated total transactions for each calendar year to compare performance over time.

3. Monthly Sales by Region: Analyzed regional sales trends for each month to identify seasonality or location-specific patterns.

4. Platform-wise Transactions: Summarized transactions for each platform (Retail and Shopify) to understand their usage trends.

5. Sales Percentage: Retail vs. Shopify: Computed the monthly percentage of sales from Retail and Shopify to track platform performance.

6. Demographic Sales Analysis: Evaluated sales percentage by demographic groups for each year to understand customer behavior.

7. Contribution of Age Bands to Retail Sales: Identified which age_band and demographic groups contributed the most to Retail platform sales.

### Code Snippets
1. Data Cleansing:
   
   ![image](https://github.com/user-attachments/assets/a4753816-37a7-4d89-83f7-1897911b0d56)

 Ouput:
 
 ![image](https://github.com/user-attachments/assets/b13c42ac-5365-45a8-9a30-289ba098462c)

 2. Example Insight: Total Transactions by Year
    ![image](https://github.com/user-attachments/assets/0296e10b-3fa6-430f-9971-ab0e1896c680)

    Output:
    
    ![image](https://github.com/user-attachments/assets/0eeb0d9f-b8cd-416a-a0ac-72f5d7231cda)



   
