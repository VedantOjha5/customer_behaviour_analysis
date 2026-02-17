🛍️ Customer Shopping Behavior Analysis

Uncovering insights from transactional data to drive strategic retail decisions

📌 Project Overview

This project focuses on analyzing customer shopping behavior using transactional retail data to uncover meaningful insights into:

Spending patterns

Customer segmentation

Product preferences

Subscription impact

Discount effectiveness

The analysis empowers businesses to make data-driven decisions that improve revenue, customer loyalty, and marketing performance.

🎯 Business Problem Statement

A leading retail company aimed to better understand evolving customer purchasing behavior across demographics, product categories, and shopping channels.

Key business question:

How can consumer shopping data be leveraged to identify trends, improve customer engagement, and optimize marketing and product strategies?

📂 Dataset Summary
Attribute	Details
Total Records	3,900 purchases
Total Features	18 columns
Data Type	Transactional retail data
Key Feature Groups

1. Customer Demographics

Age

Gender

Location

Subscription Status

2. Purchase Details

Item Purchased

Category

Purchase Amount

Season

Size & Color

3. Shopping Behavior

Discount Applied

Promo Code Used

Previous Purchases

Purchase Frequency

Review Rating

Shipping Type

🧹 Data Preparation & Cleaning (Python)

Data preprocessing was performed to ensure analytical accuracy and consistency.

Steps Performed

Data loading using pandas

Structure inspection with .info() and .describe()

Missing value treatment

37 missing values in Review Rating

Imputed using median rating per category

Column renaming to snake_case

Feature engineering:

age_group segmentation

purchase_frequency_days

Redundancy removal:

Dropped promo_code_used

Data consistency validation

Database integration with PostgreSQL

🗄️ Database & SQL Analysis

Cleaned data was imported into PostgreSQL to simulate business transactions and perform structured querying.

Key Business Analyses

Revenue by Gender

High-Spending Discount Users

Top Rated Products

Shipping Type Comparison

Subscribers vs Non-Subscribers

Discount-Dependent Products

Customer Segmentation

Top Products per Category

Repeat Buyers & Subscription Correlation

Revenue by Age Group

📊 Exploratory Data Insights
💰 Revenue by Gender

Male: $157,890

Female: $75,191

➡️ Male customers generated significantly higher revenue.

🥇 Top 5 Products

Gloves

Sandals

Boots

Hat

Skirt

🚚 Shipping Insights
Shipping Type	Avg Purchase
Express	$60.48
Standard	$58.46

➡️ Express users spend slightly more.

💳 Subscription Revenue
Segment	Total Revenue
Subscribers	$62,645
Non-Subscribers	$170,436

➡️ Large conversion opportunity exists.

🏷️ Discount Dependency

Hat → 50% discounted purchases

Sneakers → 49.66% discounted

➡️ Certain products rely heavily on discounts.

👥 Customer Segmentation

Customers were classified using purchase history:

Segment	Customers
New	83
Returning	701
Loyal	3,116

➡️ Strong loyal customer base identified.

🛒 Top Products by Category
Category	Top Product	Purchases
Accessories	Jewelry	171
Clothing	Blouse	171
Footwear	Sandals	160
Outerwear	Jacket	163
📊 Power BI Dashboard

An interactive dashboard was developed to visualize:

Revenue distribution

Customer segments

Product performance

Shipping trends

Discount impact

Dashboard Capabilities

Dynamic filtering

Category drill-downs

Demographic slicing

Revenue comparisons

💡 Business Recommendations
1️⃣ Boost Subscriptions

Promote exclusive subscriber benefits to increase retention and recurring revenue.

2️⃣ Strengthen Loyalty Programs

Reward repeat buyers to convert returning customers into loyal advocates.

3️⃣ Optimize Discount Strategy

Reduce margin loss by identifying products overly dependent on discounts.

4️⃣ Targeted Marketing

Focus campaigns on:

High-revenue demographics

Express shipping users

Loyal customers

5️⃣ Product Positioning

Promote top-rated and best-selling items in advertisements.

🧰 Tech Stack
Tool	Purpose
Python (Pandas, NumPy)	Data Cleaning & EDA
PostgreSQL	Data Storage & SQL Analysis
SQL	Business Querying
Power BI	Visualization Dashboard
📁 Repository Structure
Customer-Shopping-Behavior-Analysis/
│
├── data/
├── python-scripts/
├── sql-queries/
├── powerbi-dashboard/
├── reports/
├── presentation/
└── README.md

🚀 Project Deliverables

✔️ Cleaned & modeled dataset

✔️ Python preprocessing scripts

✔️ SQL business queries

✔️ Power BI dashboard

✔️ Project report

✔️ Stakeholder presentation

📈 Impact of the Project

This analysis enables retailers to:

Increase customer lifetime value

Improve marketing ROI

Personalize customer experiences

Optimize pricing & discounting

Strengthen loyalty programs

🤝 Contributing

Contributions, suggestions, and feedback are welcome.
Feel free to fork the repo and submit a pull request.

📬 Contact

For collaboration or queries:

Author: Himanshu Batham
Field: Data Analytics / AI / Software Development
