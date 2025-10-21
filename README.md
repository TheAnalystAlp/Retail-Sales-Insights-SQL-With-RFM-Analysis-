# Retail Sales Insights | SQL (With RFM Analysis)
# Overview
This project demonstrates end-to-end SQL data analysis on a fictional retail store dataset.  
I have covered every stage of the data analytics lifecycle — from data validation and cleaning to exploratory analysis and advanced customer segmentation (RFM).

# Objective
The goal is to uncover actionable business insights to find the optimal marketing campaign launch conditions by asking :
- Who are the most valuable and frequent customers?  
- Which products and categories drive the most revenue?  
- When is the best time to launch marketing campaign?
- What is the best way to launch marketing campaign?  
- How can RFM segmentation help identify customer loyalty and retention opportunities?

# Data Set
The dataset was originally sourced from Kaggle; however, I modified it to better suit the specific needs of my project.
Please refer to repository for the altered data set.It contains;

* Transaction_ID:A unique identifier assigned to each transaction. 
* Customer_ID:A unique identifier for each customer
* Category:The general classification of the purchased item 
* Item_ID:A unique code assigned to each product or item. 
* Price_Per_Unit:The cost of one unit of the item purchased. Useful for calculating total spending and identifying pricing trends.
* Quantity:The number of units purchased in the transaction.
* Total_Spent:The total monetary value of the transaction for that item.
* Payment_Method:The method used by the customer to complete the purchase (e.g., Credit Card, Cash, Online Payment). Useful for payment trend analysis.
* Location:The store, city, or region where the transaction took place. Helpful for geographic sales analysis and regional performance comparison.
* Transaction_Date:The date (and possibly time) when the transaction occurred. Essential for time-based analyses, such as monthly sales or seasonal trends.
* Discount_Applied:Indicates whether a discount was used in the transaction (could be a binary indicator or percentage value). Useful for assessing the impact of promotions on sales and customer behavior.

# Tools & Techniques
* MySQL 
* Window Functions (ROW_NUMBER, COUNT, SUM)**
* CTEs for segmentation**
* RFM Scoring System

# Project Overview

_ _At first glance, the data looked messy — inconsistent category names, missing values represented as \N, and even some potential duplicates. So before doing any complex analysis, I focused on one thing: getting the data right.__

1. Data Validation:Ensured that all records have been implemented and data integrity is intact.
2. Data Staging:Created staging tables for safe data cleaning and transformation.
3. Data Cleaning & Missing Values:Handle missing values and standardize inconsistent entries.
4. Duplicate Handling:Removed that duplicate transactions while maintaining a clean dataset.
5. Final Data Standardization:Ensured that consistent and accurate categorical data.
6. Exploratory Data Analysis (EDA):Analysis to understand when,how,where,which product to launch to  marketing campaign on.
7. Advanced Analysis: RFM Segmentation
8. Summary of Insights will be shown below

# Results / Insights 

Based on the data (limited to the top 10 for clarity), we can see that the highest average order value belongs to the “Butchers” category, with Customer_5 leading in total spending. This customer also shows significant spending in the Beverages category. Similarly, Customer_13 demonstrates considerable spending in Electric Household Essentials and Food. Therefore, if the campaign were to target specific customers, focusing on these high-value individuals could maximize the overall return and campaign effectiveness.
<img width="1200" height="1200" alt="1" src="https://github.com/user-attachments/assets/bc3744ad-ec70-4346-97e5-288f780a56eb" />

<img width="499" height="155" alt="1" src="https://github.com/user-attachments/assets/414a32a6-472b-43f6-b0d9-e60a3e71bb0f" />

# Project Overview

Feel free to reach me at; Linkedin:www.linkedin.com/in/alp-tuna

My Website:https://alptheanalyst.wixsite.com/alptuna

My E-Mail:alptuna.professional@gmail.com

Link for the Colab file:[https://colab.research.google.com/drive/1oXrwRaj9hJYkiJVktSucdZ0gkGIsQ_VA ](https://colab.research.google.com/drive/1lP6t4pHuJGTe1LO0ynJ8ypPAcn7KwVjc?usp=sharing)

