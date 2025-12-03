# customer_behavior_analysis
 Overview

This project performs a complete end-to-end data analysis workflow using a real-world customer shopping behavior dataset.
It covers everything from data loading, cleaning, and exploratory analysis in Python, to SQL-based analytics in PostgreSQL, and finally building a Power BI dashboard with a business report and presentation.

The goal is to uncover patterns in customer spending, product preferences, subscription behavior, and key drivers behind high-value customers.

📂 Dataset Summary

Rows: 3,900

Columns: 18

Data Includes:

Customer demographics: Age, Gender, Location, Subscription Status

Purchase info: Item, Category, Purchase Amount, Season, Size, Color

Shopping behavior: Discount Used, Promo Code Used, Previous Purchases, Purchase Frequency

Ratings & Logistics: Review Rating, Shipping Type

Missing Values: 37 missing entries in Review Rating

Source: Uploaded raw CSV file (customer_shopping_behavior.csv)

🛠️ Tools & Technologies

Python – Data loading, cleaning, preprocessing, EDA
Libraries: Pandas, NumPy, Matplotlib, Seaborn
Jupyter Notebook / VS Code – Development environment
PostgreSQL – SQL querying and structured data analysis
pgAdmin – Database management
Power BI – Dashboard creation
MS Word / Google Docs – Business report
PowerPoint – Final presentation deck

🚀 Project Steps
1. Load the Dataset (Python)

Imported CSV using Pandas

Reviewed data types, column names, missing values

Generated initial summary statistics

2. Exploratory Data Analysis (EDA)

Distribution analysis (purchase amount, age, ratings)

Boxplots, category-wise comparisons

Outlier detection

3. Data Cleaning & Feature Engineering

Removed duplicate rows

Handled missing review ratings by imputing category-wise medians

Standardized column names to snake_case

Created additional features:

age_group (binned age values)

purchase_frequency_days

Removed redundant column promo_code_used

4. SQL Analysis (PostgreSQL)

The cleaned dataset was loaded into PostgreSQL for structured analysis.
Key SQL insights generated:

Revenue by Gender

High-Spending Customers with Discounts

Top 5 Products by Average Rating

Shipping Type Comparison (Standard vs Express)

Subscribers vs Non-Subscribers Analysis

Products Most Dependent on Discounts

Customer Segmentation (New, Returning, Loyal)

Top 3 Products in Each Category

Repeat Buyers & Subscription Likelihood

Revenue Contribution by Age Group

📊 Power BI Dashboard

An interactive dashboard visualizes key findings, including:

KPI Panel: Total Revenue, Avg Purchase Amount, Total Customers

Customer Purchase Patterns

Revenue & Profit Trends

Top Product Categories & Best Sellers

Age Group & Gender Insights

Filters: Date, Category, Gender, Subscription Status

📈 Key Results & Insights

Female customers contributed slightly more total revenue than male customers.

Customers using Express Shipping tended to spend more.

20% of customers generated nearly 60% of overall revenue.

Loyal customers (5+ purchases) showed higher subscription adoption.

Discount-heavy categories attracted price-sensitive segments.

Top-rated products overlapped with most frequently purchased items, indicating strong customer satisfaction.

💡 Business Recommendations

Boost Subscriptions: Introduce exclusive rewards for subscribers.

Loyalty Programs: Incentivize repeat buyers to move them into the “Loyal” segment.

Optimize Discount Strategy: Balance between sales uplift and profit margin.

Feature Top-Rated Products: Promote best-selling and high-rated items.

Target High-Value Segments: Focus marketing on profitable age groups and express-shipping users.
