# Retail Sales Performance Dashboard | SAP Analytics Cloud

An interactive sales dashboard built in SAP Analytics Cloud (SAC) on a sample retail dataset of 950 transactions.

## Dashboard Preview
![Dashboard](screenshots/dashboard.png)

## Objective
Analyse revenue performance across products, cities, customer segments and time to support sales and marketing decisions.

## Data
- Sample retail dataset: 950 transactions, 13 fields (Transaction ID, Date, Month, Customer ID, Gender, Age, Age Group, City, Product Category, Quantity, Price per Unit, Total Amount, Payment Mode)
- Synthetic dataset created for practice, not real company data

## Data Preparation
- Uploaded the Excel file to SAC and set measures (Quantity, Price per Unit, Total Amount) and dimensions (all other fields)
- Created derived fields: Age Group (18-24 to 55+) and Month
- Configured the Month hierarchy for the trend analysis

## Dashboard Features
- KPI tiles: Total Revenue (10.08M) and Total Units Sold (2,870)
- Charts: revenue by product category, city, payment mode and age group, plus a monthly revenue trend
- Filters: Month, Product Category and City

## Key Insights
1. Electronics drives about 58% of total revenue; Books is the lowest at about 1.4%.
2. Chennai and Bengaluru are the top cities by revenue.
3. Monthly revenue varies widely, peaking at about 1.28M and dipping to about 0.63M.
4. The 45-54 age group contributes the most revenue (about 25%).
5. Payment modes are evenly spread, with no single dominant mode.

## Tools
SAP Analytics Cloud, Excel, data modelling, data visualisation
