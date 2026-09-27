📌 Project Overview

The PhonePe Payment Analytics Dashboard is an interactive Power BI dashboard developed to analyze digital payment transactions, transaction value, users, services, customer demographics, and transaction trends.

The dashboard provides a centralized view of important business KPIs and helps identify transaction patterns and performance trends.
🎯 Objectives

    Analyze total transactions and transaction value.

    Track monthly transaction trends.

    Calculate Month-over-Month (MOM) growth.

    Monitor total users.

    Analyze transaction success rate.

    Compare weekday and weekend transactions.

    Analyze transaction value by service type.

    Identify top 5 users by transaction value.

    Analyze users based on age segments.

🛠️ Technologies Used

    Power BI

    Power Query

    DAX

    Excel / Dataset

    Data Modeling

    Data Visualization

📊 Dashboard Features
KPI Cards

    Total Transactions

    Total Transaction Value

    Total Users

    Success Rate

    Transaction MOM %

    Transaction Value MOM %

Visualizations

    Monthly Transaction Value Trend

    Transaction Value by Service Type

    Weekday vs Weekend Transactions

    Top 5 Users by Transaction Value

    Users by Age Segment

    Interactive Month Filter

🧮 DAX

Example measures used in the project:

Total Transaction =
COUNTROWS(All_Transactions)

Success Rate =
DIVIDE(
    [Total Successful Transaction],
    [Total Transaction]
)

Time-intelligence measures are also used for calculating Month-over-Month transaction and transaction-value growth.
📅 Date Analysis

A dedicated date table is used for time-based analysis.

It contains:

    Date

    Year

    Month

    Month Number

    Quarter

    Weekday

    Day Number

This enables monthly trends and MOM analysis.
📈 Key Analysis

The dashboard analyzes:
Analysis	Purpose
Transaction Analysis	Monitor transaction volume
Value Analysis	Analyze transaction value
Service Analysis	Compare different services
User Analysis	Understand customer activity
Age Analysis	Analyze demographic segments
Time Analysis	Identify monthly trends
Weekend Analysis	Compare weekday/weekend activity
💡 Business Insights

The dashboard can help identify:

    Monthly transaction growth patterns.

    High-performing services.

    High-value users.

    User demographic distribution.

    Peak transaction periods.

    Weekday and weekend transaction behavior.

    Overall transaction performance.

👨‍💻 Skills Demonstrated

    Data Cleaning

    Data Transformation

    Data Modeling

    DAX

    Power BI

    Data Visualization

    KPI Creation

    Time Intelligence

    Business Analysis

    Dashboard Design

📂 Project Files

PhonePe-Payment-Analytics/
│
├── Phonepay_DATA.pbix
├── README.md
├── Dashboard-Screenshot.png
└── Dataset.xlsx
