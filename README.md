# Telco Customer Churn Dashboard (Power BI)

## Problem
Why are customers leaving, and which customer groups are most at risk?

## Dataset
Telco Customer Churn sample dataset (7,043 customers, 21 columns), publicly available on Kaggle. Source: [https://www.kaggle.com/datasets/blastchar/telco-customer-churn?utm_source=chatgpt.com]

## Tools
Power BI Desktop (Power Query, DAX)

## What I did
1. Cleaned TotalCharges in Power Query (11 blank values for new customers set to 0)
2. Created a Tenure Group column using DAX
3. Created measures: Total Customers, Churned Customers, Churn Rate, Avg Monthly Charges, Monthly Revenue Lost
4. Built a 2-page dashboard: **Overview** and **Churn Drivers**
5. Added Gender and Contract slicers for filtering

## Key findings
- 26.5% of customers churned (1,869 of 7,043)
- Month-to-month contracts churn at 42.7%, vs 11.3% on one-year and 2.8% on two-year contracts
- Fiber optic customers churn at 41.9%, vs 19.0% on DSL
- Customers in their first year churn at 47.4%, vs 9.5% for customers with 49+ months
- Electronic check payers churn at 45.3%, vs 15–19% for other payment methods
- Churned customers pay more on average ($74.44 vs $61.27 per month)
