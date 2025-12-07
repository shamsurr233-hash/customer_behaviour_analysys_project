## Customer Shopping Behavior Analysis

A complete end-to-end data analytics project analyzing 50,000 customer transactions across multiple product categories.
This project explores spending behavior, customer segmentation, product preferences, discount usage, and subscription patterns using Python + SQL + MySQL.

## 1. Project Overview

This project analyzes customer shopping behavior using transactional data from 50,000 purchases.
The goal is to uncover insights about:

Spending patterns

Customer segments

Product performance

Discount impact

Subscription behavior

These insights support strategic decisions in marketing, product placement, and customer retention.

## 2. Dataset Summary

Rows: 50,000

Columns: 23

Key Feature Groups

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Amount, Season, Size, Color

Behavioral Factors: Discount Applied, Promo Code Used, Review Rating, Shipping Type

History & Frequency: Previous Purchases, Purchase Frequency

📌  dataset preview 
![Dataset Preview](images/dataset_preview.png)
![Dataset Preview](images/dataset_preview.png)


🧮 3. Exploratory Data Analysis (Python)
✔️ Data Preparation & Cleaning

Loaded the dataset using pandas

Inspected structure using df.info() and summary stats via .describe()

Imputed missing Review Ratings using category-wise median

Standardized column names to snake_case

Dropped redundant columns (promo_code_used)

✔️ Feature Engineering

Created age_group from age bins

Calculated purchase_frequency_days

Added loyalty indicators based on previous purchases

✔️ Database Integration

Loaded cleaned DataFrame into PostgreSQL

Performed advanced analysis using SQL queries

📌 (Add a Python EDA screenshot here)
➡️ Suggested file: images/python_eda.png

📌 (Add an ERD / Database Diagram here)
➡️ Suggested file: images/database_erd.png

🗂️ 4. SQL Analysis

Key business questions answered using SQL:

🔍 Customer & Revenue Insights

Revenue by male vs female

Do subscribers spend more?

🔍 Product & Rating Insights

Top 5 products with highest average ratings

Most purchased products per category

Products with highest discount-usage percentage

🔍 Behavioral Insights

Customers who used discounts but still spent above average

Repeat buyers and their subscription likelihood

Revenue contribution by age groups

📌 (Add SQL query result screenshots/tables here)
➡️ Suggested files:

images/sql_gender_revenue.png

images/sql_top_products.png

images/sql_age_group_revenue.png

💡 6. Business Recommendations
⭐ Boost Subscriptions

Offer exclusive benefits and personalized discounts.

⭐ Customer Loyalty Programs

Reward returning buyers to convert them into loyal customers.

⭐ Review Discount Policy

Balance margin and customer acquisition through optimized discount rules.

⭐ Product Positioning

Feature top-rated and frequently purchased products in promotional campaigns.

⭐ Targeted Marketing

Focus on:

High-revenue age groups

Express-shipping customers

Repeat buyers

🔧 Tech Stack
Category	Tools
Programming	Python (pandas, numpy, matplotlib)
Database	PostgreSQL
SQL	Window Functions, Joins, Aggregations
Data Engineering	Cleaning, Feature Engineering
Visualization	Power BI / Python
