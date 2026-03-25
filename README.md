# Customer-Behaviour-Analysis
Data analytics Project Showcasing customer behaviour through tools like python and their modules,Mysql,and Power Bi
🛒 Customer Shopping Behavior Analysis
📌 Project Overview

This project focuses on analyzing customer shopping behavior using transactional data to uncover meaningful business insights. The objective is to understand spending patterns, customer segments, product performance, and subscription behavior to support data-driven decision-making.

The analysis combines Python (EDA), SQL (business queries), and Power BI (dashboarding) to deliver an end-to-end data analytics solution.

📊 Dataset Summary
Total Records: 3,900 transactions
Total Features: 18 columns
Key Data Categories:
Customer Demographics: Age, Gender, Location, Subscription Status
Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
Behavioral Data: Discount Applied, Previous Purchases, Frequency, Review Rating, Shipping Type
Data Quality:
Missing values found in Review Rating (37 values)
Handled using median imputation based on product category
🧹 Data Cleaning & Preparation (Python)

Performed using Pandas, NumPy, and Matplotlib

Loaded and explored dataset (.info(), .describe())
Handled missing values using group-wise median
Standardized column names (snake_case format)
Created new features:
age_group (customer segmentation)
purchase_frequency_days
Removed redundant columns (promo_code_used)
Ensured data consistency and quality
Exported cleaned dataset to PostgreSQL for further analysis
🧠 Business Analysis (SQL)

Conducted advanced analysis using SQL to answer key business questions:

Revenue comparison by Gender
Identification of high-spending discount users
Top-rated products based on average review rating
Impact of shipping type on purchase amount
Comparison of Subscribers vs Non-Subscribers
Detection of discount-dependent products
Customer segmentation:
New Customers
Returning Customers
Loyal Customers
Top-performing products per category
Relationship between repeat purchases and subscriptions
Revenue contribution by age group
📈 Dashboard (Power BI)

Developed an interactive dashboard to visualize insights:

Revenue trends and breakdowns
Customer segmentation analysis
Product performance insights
Subscription behavior
Shipping and discount impact

The dashboard enables stakeholders to quickly interpret data and make strategic decisions.

💡 Key Insights & Recommendations
Increase Subscription Adoption
Offer exclusive benefits to encourage more users to subscribe.
Enhance Customer Loyalty Programs
Reward repeat customers to convert them into loyal customers.
Optimize Discount Strategy
Balance between boosting sales and maintaining profit margins.
Focus on High-Performing Products
Promote top-rated and frequently purchased products.
Targeted Marketing Campaigns
Focus on high-revenue age groups and frequent buyers.
🛠️ Tech Stack
Python: Data Cleaning & EDA
SQL (PostgreSQL): Business Analysis
Power BI: Data Visualization
Libraries Used: Pandas, NumPy, Matplotlib
