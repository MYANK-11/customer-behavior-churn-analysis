# 📊Customer Behavior & Churn Analysis

An end-to-end customer behavior and churn risk analysis project using SQL, Python, and Power BI. This project focuses on understanding customer purchase behavior, identifying revenue drivers, and detecting customers at high risk of churn using behavioral metrics.

## 🚀Project Objective

   •To analyze customer shopping behavior and answer the following business questions:

   •What factors drive revenue across age groups, gender, and product categories?

   •How do subscription status, discounts, and shipping types impact purchasing behavior?

   •How does purchase frequency relate to spending?

   •Which customers are at high risk of churn based on historical behavior?

   •The final output is an interactive business intelligence dashboard built in Power BI with a dedicated Churn Risk KPI.



## 🛠 Tech Stack

Tools & Technologies:

1.Python (Pandas, NumPy)

2.PostgreSQL

3.SQL

4.SQLAlchemy

5.Power BI

6.DAX

7.Scikit - learn


## 📂 Dataset Overview

Source File: customer_shopping_behavior.csv

Total Records: 3,900

Total Features: 18

Key Columns:-

  •customer_id

  •age, gender, age_group

  •item_purchased, category

  •purchase_amount

  •subscription_status

  •discount_applied

  •shipping_type

  •previous_purchases

  •payment_method

  •purchase_frequency_days



## ⚙️ Project Workflow (End-to-End)

    CSV Dataset → Python Data Cleaning → PostgreSQL Database → SQL Business Analysis → Power BI Dashboard → Business Decisions 


## 1️⃣ Data Cleaning (Python)

 •Removed duplicates

 •Handled missing values

Created engineered columns:

  •age_group

  •purchase_frequency_days

## 2️⃣ Data Storage (PostgreSQL)

 •Cleaned dataset loaded into PostgreSQL using SQLAlchemy

 •All analysis performed using pure SQL

## 3️⃣ SQL Business Analysis

Key analysis areas:

 •Revenue by category, age group, and gender

 •Subscription vs non-subscription behavior

 •Impact of discounts on revenue

 •Customer loyalty using previous purchase history

 •Purchase frequency vs spending behavior

 •High churn-risk customer identification

## 4️⃣ Power BI Dashboard

KPIs:

 •Number of Customers

 •Average Purchase Amount

 •High Churn-Risk Customers (Distinct KPI)

Visuals:

   •Revenue by category and age group

 •Subscription analysis

 •Purchase frequency vs spending

Filters:

 •Subscription status

 •Gender

 •Category

 •Shipping type

## 🔍 Churn Risk Logic

    Customers are classified as High Churn Risk if:

          previous_purchases >= 5

          purchase_frequency_days > 45

## The KPI is calculated using:
```
✅ Distinct count of customers
✅ Not row-level counts
✅ Not summed flags
```

## 📈 Key Business Insights

 •Subscription customers generate significantly higher repeat revenue.

 •Discount-driven customers show lower long-term loyalty.

 •Very frequent buyers tend to stabilize revenue volume more than rare buyers.

 •A large segment of historically active customers shows churn risk due to long inactivity gaps.


## ✅ Final Output

✔️ Production-grade Power BI dashboard

✔️ SQL-driven behavioral analysis

✔️ Real-time churn monitoring KPI

✔️ Executive-ready business report

    ## SQL → DAX → Dashboard → Business Decision



## 📌 Author

MAYANK P. SAVANI 

Aspiring Data Analyst | SQL | Python | Power BI
