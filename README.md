Customer Shopping Behavior Analysis
Overview

An end-to-end Data Analytics project analyzing customer shopping behavior across 3,900 purchases to uncover spending patterns, customer segments, product preferences, and subscription behavior.

Workflow:
Python → EDA & Data Cleaning → PostgreSQL → SQL Analysis → Power BI → Report & Presentation

📂 Dataset
3,900 purchase records
18 columns
Customer demographics, purchase details, shopping behavior, ratings and shipping information
37 missing values in the Review Rating column

Key attributes include:

Age | Gender | Location | Subscription Status | Item Purchased | Category | Purchase Amount | Season | Discount | Previous Purchases | Review Rating | Shipping Type

🛠️ Tools & Technologies
Python – Data loading, EDA & data cleaning
Pandas – Data manipulation
PostgreSQL – SQL-based business analysis
Power BI – Interactive dashboard
Gamma – Business presentation
GitHub – Project documentation

🔄 Project Workflow
1. Python – EDA & Data Cleaning
Loaded and explored the dataset using Pandas
Performed data structure and statistical analysis
Handled missing review ratings using category-level median values
Standardized column names
Created age_group and purchase_frequency_days
Removed redundant promo_code_used information
Loaded the cleaned dataset into PostgreSQL

3. PostgreSQL – Business Analysis

SQL queries were used to answer key business questions, including:

Revenue by gender
High-spending customers using discounts
Top-rated products
Standard vs. Express shipping spend
Subscribers vs. non-subscribers
Discount-dependent products
Customer segmentation
Top products by category
Repeat buyers and subscription behavior
Revenue by age group

3. Power BI – Dashboard

Built an interactive dashboard to visualize customer behavior, spending patterns, product performance, subscriptions, and customer segments.

📈 Key Insights
Female customers generated slightly higher total revenue than male customers.
Customers using discounts could still represent a high-value segment.
Express-shipping customers showed higher average purchase value.
Subscription customers demonstrated stronger spending and repeat-purchase behavior.
Customers were segmented into New, Returning, and Loyal groups.
Top-rated and best-selling products presented opportunities for targeted campaigns.
💡 Business Recommendations
Boost Subscriptions: Promote exclusive subscriber benefits.
Build Loyalty: Reward repeat customers and encourage progression into the Loyal segment.
Review Discount Strategy: Balance promotional activity with profitability.
Product Positioning: Promote highly rated and best-selling products.
Targeted Marketing: Focus on high-revenue customer segments and relevant shopping behaviors.


🎯 Skills Demonstrated

Python | Pandas | EDA | Data Cleaning | SQL | PostgreSQL | Power BI | Customer Segmentation | Data Visualization | Business Analysis | Data Storytelling
