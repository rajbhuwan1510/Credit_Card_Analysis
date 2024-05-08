# Credit Card Financial Analysis Project

## Overview
Welcome to the Credit Card Financial Analysis Project repository! This project aims to provide insights into credit card transactions and customer demographics using Power BI. The data is sourced from PostgreSQL and includes two main tables: `cc_detail` containing credit card transaction details and `cust_detail` containing customer demographics.

## Data Source
The data includes the following key attributes:
- **cc_detail Table**: Contains information about credit card transactions, including client number, card category, annual fees, transaction amounts, and more.
- **cust_detail Table**: Contains customer demographics such as age, gender, education level, income, and satisfaction score.

## Power BI Dashboards
This project includes two main Power BI dashboards:
1. **Credit Card Transaction Analysis Dashboard**: Provides insights into credit card transactions, including total revenue, interest earned, quarterly revenue trends, and week-on-week growth measures.
2. **Credit Card Customer Report Dashboard**: Focuses on customer demographics, including age and gender distribution, income analysis, and satisfaction score breakdown.

## Usage
To utilize the Power BI reports, follow these steps:
1. **Data Preparation**: Write SQL queries to load data from PostgreSQL into Power BI.
2. **Import Data**: Import the data into Power BI and ensure data cleaning steps such as removing duplicates and formatting dates are performed.
3. **Data Modeling**: Create DAX queries for measures such as revenue calculation, age grouping, and income categorization.
4. **Dashboard Exploration**: Explore the dashboards to gain insights into credit card transactions and customer demographics.

## DAX Queries
Here are some sample DAX queries used in this project:
- **AgeGroup**: Categorizes customers into age groups (20-30, 30-40, 40-50, 50-60, 60+).
- **IncomeGroup**: Categorizes customers based on income levels (Low, Medium, High).
- **Revenue**: Calculates total revenue by summing annual fees, transaction amounts, and interest earned.
- **Current_week_Revenue**: Calculates revenue for the current week.
- **Previous_week_Revenue**: Calculates revenue for the previous week.

## Insights
Here are some key insights from the project:
- Week 53 (31st Dec) saw a significant increase in revenue and transaction amounts compared to the previous week.
- Year-to-date (YTD) revenue reached 57 million, with a total interest of 8 million.
- Male customers contribute more to revenue than female customers.
- Blue and Silver credit cards account for 93% of overall transactions.
- The states of TX, NY, and CA contribute to 68% of total transactions.
- The activation rate is 57.5%, and the delinquent rate is 6.06%.

## Conclusion
The Credit Card Financial Analysis Project provides valuable insights into credit card transactions and customer demographics, enabling better decision-making and strategy development for financial institutions. Explore the dashboards to uncover more insights and trends in credit card usage and customer behavior.
