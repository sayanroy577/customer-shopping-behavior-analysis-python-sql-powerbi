# customer-shopping-behavior-analysis-python-sql-powerbi
🛍️ Customer Shopping Behavior Analysis

Uncovering insights from 3,900 retail transactions to drive data-informed business decisions.

🧭 Overview

This project analyzes customer shopping behavior for a leading retail company using Python, MySQL, and Power BI. The goal is to understand what drives purchase patterns, customer loyalty, and revenue growth — transforming raw data into actionable business intelligence.

❓ Problem Statement

The company aims to understand changing customer shopping behavior to improve sales, satisfaction, and retention.
Management wants to identify key factors such as discounts, reviews, seasons, and payment preferences influencing customer decisions and repeat purchases.

Core Business Question:

How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?

📊 Dataset

Source: Consumer shopping transactions

Records: 3,900

Features: 18

Missing Values: 37 (in Review Rating)

Key Attributes:

Customer demographics — Age, Gender, Location, Subscription Status

Purchase details — Item Purchased, Category, Amount, Season, Size, Color

Behavior — Discounts, Promo Codes, Frequency, Reviews, Shipping Type

🧰 Tools & Technologies
Tool	Purpose
Python (Pandas, NumPy)	Data loading, cleaning, preprocessing
MySQL Server	SQL queries and business analysis
Power BI	Interactive dashboard and visualization
MS Excel	Basic data validation and export
PowerPoint / PDF	Report documentation and presentation
🔍 Steps Followed
1. Data Loading & Cleaning (Python)

Imported dataset using Pandas

Checked data types and statistics (df.info(), df.describe())

Replaced 37 missing review values with median ratings by category

Standardized column names (snake_case formatting)

Created new column: purchase_frequency_days

Removed redundant columns (promo_code_used)

Exported cleaned dataset to MySQL

2. Data Analysis (MySQL)

Executed SQL queries to extract business insights:

Revenue comparison by gender

Top customers spending high despite discounts

Products with highest average reviews

Revenue analysis by shipping type

Subscription vs Non-subscription spending comparison

Top 3 items per category

Customer classification (new, loyal, returning)

Seasonal sales and product trends

Color-based product popularity

3. Dashboard Development (Power BI)

Designed an interactive Power BI dashboard to visualize:

Total revenue, average spend, and category trends

Gender and subscription-based comparisons

Seasonal product performance

Customer segmentation and frequency metrics

📈 Dashboard Overview

Key Visuals:

Revenue by gender and shipping type

Subscriber vs Non-subscriber spend

Top-rated and most purchased products

Seasonal and color-based trends

Customer segmentation (New, Loyal, Returning)

💡 Key Insights

Subscribers spend 68% more and contribute 3.2× revenue than non-subscribers

Express shipping customers generate the highest average order value

Top-rated products (4★+) have 2.3× higher repeat purchase rates

Loyal customers (2–15 purchases) form the most profitable segment

Seasonal campaigns significantly influence category-level performance

Colors like Olive, Yellow, Silver dominate sales preferences

🧠 Results & Recommendations

Boost Subscriptions: Offer free shipping, early access, and rewards

Enhance Loyalty Programs: Tier-based incentives to increase frequency

Optimize Discounts: Focus on value perception over deep discounts

Promote Top-Rated Products: Use customer ratings in marketing

Personalized Marketing: Age-group targeting and email re-engagement

Expand Popular Variants: Increase stock of high-demand colors

Improve Low-Rated Items: Analyze feedback to enhance quality

🧩 Conclusion

This end-to-end analytics project demonstrates how data can reveal valuable insights into customer behavior. The findings empower businesses to make data-driven decisions, enhance customer engagement, and maximize profitability through informed marketing and product strategies.

⚙️ How to Run the Project
Prerequisites

Python 3.9+

MySQL Server

Power BI Desktop

Steps

Clone this repository:

git clone https://github.com/yourusername/customer-behavior-analysis.git


Install dependencies:

pip install pandas numpy mysql-connector-python


Load dataset and clean in Python:

python data_cleaning.py


Import cleaned data into MySQL and run SQL scripts from /sql/queries.sql

Open Power BI file (dashboard.pbix) to view interactive dashboard.

Refer to /reports/Customer_Behavior_Report.pdf for summarized findings.

📁 Project Deliverables

Cleaned dataset (/data/cleaned_data.csv)

SQL scripts (/sql/queries.sql)

Power BI Dashboard (/dashboard/dashboard.pbix)

Final Report (/reports/Customer_Behavior_Report.pdf)
