Banking KPI Dashboard – Power BI Project
Project Overview

This project is a multi-page Banking KPI Dashboard built in Power BI using a Bank Customer Churn dataset from Kaggle.

The dashboard focuses on customer churn analysis, customer demographics, and banking deposit insights through interactive visualizations and DAX measures.

Dataset used:
Bank Customer Churn Dataset (Kaggle)

Tools Used
- Power BI
- Power Query
- DAX
- Data Visualization
- Data Cleaning & Preparation

Using Power Query:

- Removed null values
- Removed blank rows
- Fixed data types
- Renamed columns
- Created age groups (bins)
- DAX Measures
- Total Customers = COUNTROWS(Customers)

- Churned Customers =
CALCULATE(
    COUNTROWS(Customers),
    Customers[Exited] = 1
)

- Churn Rate =
DIVIDE([Churned Customers], [Total Customers])

- Avg Balance =
AVERAGE(Customers[Balance])
Dashboard Pages
Page 1 — Customer Overview

Visuals included:

KPI Card: Total Customers
KPI Card: Churn Rate %
Bar Chart: Customers by Country/Region
Line Chart: Balance Trend by Age Group
Page 2 — Deposits & Balances

Visuals included:

KPI Card: Average Balance
KPI Card: Total Deposits
Donut Chart: Balance by Product Type
Bar Chart: Top Segments by Balance
Page 3 — Demographics

Visuals included:

Bar Chart: Customers by Age Group
Pie Chart: Gender Split
Interactive Slicers:
Country Filter
Product Filter
Dashboard Design

To create a banking-style professional dashboard:

Dark blue + white color scheme
Main dashboard color: #1F4E79
Consistent chart formatting
Clean labels and titles
Banking KPI Dashboard branding
Key Skills Practiced
Data cleaning in Power Query
DAX calculations
KPI dashboard creation
Interactive report design
Banking data analysis
Data storytelling

## Dashboard Preview

### Customer Overview
![Page 1](screenshots/page1.png)

### Deposits & Balances
![Page 2](screenshots/page2.png)

### Demographics
![Page 3](screenshots/page3.png)


Author

Somaye Shafiee
