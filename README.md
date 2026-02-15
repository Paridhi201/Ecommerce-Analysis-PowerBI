Author: Paridhi Yadav

1. Business Objective 

Analyze customer behavior, sales trends, and product performance to identify key revenue drivers and provide actionable business insights for growth and customer retention.

2. Dataset Overview

The dataset contains 10,000 transaction records and includes three main categories:

Order Details

order_id

order_date

revenue

quantity

delivery_days

Customer Information

customer_id

customer_segment

customer_gender

is_repeat_customer

country, city

customer_rating

Product Information

product_category

product_name

Data was loaded into Power BI and validated using Power Query column profiling to check for:

Missing values

Nulls

Unique records

Data consistency

All order_id values were unique, confirming no duplicate transactions.

Key Metrics Created (DAX)

Total Revenue

Total Customers (Distinct Count)

Repeat Customer %

Total Quantity Sold

Average Delivery Time

Days to First Purchase after Signup

Average Customer Rating

Customer Age Group

3. Key Business Insights
1. Slow Customer Conversion

Customers took more than 6 months on average to make their first purchase after signup.
Implication: Improve onboarding, retargeting, and trust-building campaigns to reduce conversion time.

2. Customer Satisfaction Opportunity

Average rating: 3.76 (< 4)
Implication: Improve delivery timelines and product quality to increase customer satisfaction.

3. Revenue Concentration in Top Cities

Top 5 cities (Toronto, London, New Delhi, Berlin, Manchester) contributed ~50% of total revenue.
Implication: Focus marketing and operational expansion in high-performing cities.

4. Strong Dependence on Repeat Customers

Repeat customers contributed over 50% of revenue.
Implication: Invest in loyalty programs, targeted offers, and retention strategies.

5. Revenue Decline After June

A significant drop (~150K) was observed in June–July, with continued lower performance in the second half of the year.
Possible Reasons:

Operational issues

Reduced marketing activity

Increased competition

Customer & Product Segmentation Insights

Men spent more than women in the Beauty category, indicating an opportunity for targeted male-focused promotions.

Revenue contribution across customer segments was evenly distributed, showing balanced segment importance.

Male and female customers contributed almost equally to overall revenue.

Dashboard Highlights

KPI Cards: Revenue, Customers, Repeat Rate, Rating

Revenue Trend by Month

Orders by City

Customer Age Group Distribution

Product & Category Performance

Gender-wise Spending Analysis

<img width="1164" height="732" alt="image" src="https://github.com/user-attachments/assets/7cc75c3b-ee4e-4c1e-b9b5-0867ca4927e7" />

<img width="1163" height="776" alt="{980DE395-C899-4935-BAC7-0DAE45C39534}" src="https://github.com/user-attachments/assets/46515eb6-f914-493d-ac6a-312cfd1334c1" />

<img width="1165" height="782" alt="{B4E531C5-7C45-4A7E-8B9A-DAE6DAE7CB09}" src="https://github.com/user-attachments/assets/ab28b06b-31fd-456f-9ef1-a9bca7fae1da" />




Tools Used - 

Power BI

DAX

Power Query
