# Retail Sales Insights | SQL (With RFM Analysis)

1. Identify Highest Spending Customers and Their Favorite Categories
Analyze customer purchase data to find the top spenders in your stores.
Determine which product categories these high-value customers spend the most on.
This helps understand customer preferences and prioritize offerings.
2. Determine Products and Categories to Prioritize
Based on frequent customer purchases, identify the products and categories with the highest demand.
Use this information to focus inventory, promotions, and marketing efforts on these priority items.
3. Analyze Past Sales Trends to Find the Optimal Campaign Timing
Review sales data from 2024 to identify seasonal patterns and peak purchasing periods.
Determine the time of year, month, or week when your target customers are most active.
Use this insight to schedule the campaign for maximum impact.
4. Recommend the Best Campaign Launch Strategy
Decide on the type of campaign (email, social media, in-store promotion, or multi-channel).
Tailor messaging to high-value customers and highlight prioritized products and categories.
Combine timing insights with targeted promotions to maximize engagement and ROI.

At first glance, the data looked messy — inconsistent category names, missing values represented as \N, and even some potential duplicates. So before doing any complex analysis, I focused on one thing: getting the data right.

# Project Overview

1.Data Validation:Ensured that all records have been implemented and data integrity is intact.
2.Data Staging:Created staging tables for safe data cleaning and transformation.
3.Data Cleaning & Missing Values:Handle missing values and standardize inconsistent entries.
4.Duplicate Handling:Removed that duplicate transactions while maintaining a clean dataset.
5.Final Data Standardization:Ensured that consistent and accurate categorical data.
6.Exploratory Data Analysis (EDA):Analysis to understand when,how,where,which product to launch to  marketing campaign on.
7Advanced Analysis: RFM Segmentation
8.Summary of Insights will be shown below

# Tools & Techniques
*MySQL / SQL**
*Window Functions (ROW_NUMBER, COUNT, SUM)**
*CTEs for segmentation**
*RFM Scoring System**
