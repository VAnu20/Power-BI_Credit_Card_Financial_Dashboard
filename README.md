# **Power-BI_Credit_Card_Financial_Dashboard**

An interactive Power BI analytics dashboard that provides insights into credit card customer behavior and transaction performance. The project focuses on analyzing financial data to help stakeholders monitor key performance indicators (KPIs), understand spending patterns, and identify profitable customer segments.

## Table of Contents
- [Project Overview](#project-overview )
- [Project Objective](#project-objective)
- [Dataset Used](#dataset-used )
- [Tools & Technology Used](#tools-&-technologies-used)
- [Technical Implementation](#technical-implementation)
- [Dashboard 1 – Credit Card Customer Report](#dashboard-1-–-credit-card-customer-report)
- [Dashboard 2 – Credit Card Transaction Report](#dashboard-2-–-credit-card-transaction-report)
- [Key Business Insights/Findings](#key-business-insights/findings)
- [Conclusion](#Conclusion)

### Project Overview 

This project was developed to create an interactive reporting solution using Power BI that tracks credit card operations and customer activity. The dashboards enable business stakeholders to monitor revenue, transaction trends, and customer demographics, helping them make data-driven decisions.

The project includes two dashboards:

**1️. Credit Card Customer Dashboard**

**2️. Credit Card Transaction Dashboard**

Both dashboards are interactive and allow filtering by Gender, Age Group, Income Group, Transaction Date, and Spending Category.

### Project Objective 

As part of this task, you are required to build two interactive Power BI dashboards from the provided datasets. The dashboards should provide actionable insights and be filtered by gender (Male/Female). The primary focus is to create meaningful visualizations based on key metrics related to Credit Card Customers and Credit Card Transactions.

- **The primary objectives of this project include:**

  - Developing interactive Power BI dashboards to analyze credit card data
  - Monitoring key performance indicators such as revenue, interest earned, and transaction volume
  - Identifying customer demographics contributing the most to revenue
  - Analyzing customer behavior based on age group, gender, and income level
  - Understanding transaction trends across different spending categories
  - Providing a weekly financial performance overview for business stakeholders

### Dataset Used 

The primary dataset used for this analysis can be found in the files uploaded to this repository. 

### Tools & Technologies Used

- **Excel:** For ensuring accuracy and consistency in data for reliable analysis.
- **Power BI:** For designing interactive dashboards.

  - Power BI
  - Power Query (ETL)
  - DAX (Data Analysis Expressions)
  - Data Modeling
  - Data Visualization

### Technical Implementation
- **1.Data Extraction & Cleaning (Power Query)**
  - Imported datasets into Power BI
  - Performed data profiling to detect missing values
  - Standardized data formats
  - Created Age Groups and Income Groups
  - Cleaned and transformed raw data for analysis

- **2.Data Modeling**

A **relationship model** was created between:
  - Customer Table
  - Credit Card Transaction Table
The Customer ID column was used as the primary key to establish relationships.

### Dashboard 1 – Credit Card Customer Report
The Customer Dashboard focuses on analyzing customer demographics and identifying key customer segments contributing to revenue.

- **Key Insights Provided**
  - Distribution of customers by gender
  - Segmentation of customers by **age groups**
  - Customer analysis based on **income groups**
  - Revenue contribution from different **demographic segments**

- **Filters Available**
  - Gender (Male/Female)
  - Age Group
  - Income Group
These filters allow users to dynamically analyze customer behavior across different demographics.

  ![Screenshot](https://github.com/VAnu20/Power-BI_Credit_Card_Financial_Dashboard/blob/dc51e8a896ed9cbeda3a21816672780d26f68eb8/Credit_Card_Financial_Dashboard-Customer.pdf)

### Dashboard 2 – Credit Card Transaction Report
The Transaction Dashboard provides insights into credit card usage patterns and financial performance.

- **Key Metrics Analyzed**
  - Total Revenue
  - Total Interest Earned
  - Total Transaction Amount
  - Transaction Count
  - Revenue by Card Type
  - Spending by Category
  - Weekly Revenue Trends

- **Filters Available**
  - Gender
  - Transaction Date(Week Filter)
  - Spending Category
This dashboard helps analyze spending patterns and transaction trends across time.

  ![Screenshot](https://github.com/VAnu20/Power-BI_Credit_Card_Financial_Dashboard/blob/3e558bd826327290863b15dfe517edd9794bee1b/Credit_Card_Financial_Dashboard-Transaction.pdf)

### Key Business Insights/Findings

- **Week-over-Week Performance**
  - Revenue increased by **28.8%**
  - Total transaction amount increased by **35.1%**
  - Transaction count increased by **3.39%**
  - Customer count increased by **8.9%**

- **Overall Performance (Year-to-Date)**
  - Total Revenue generated: **57M**
  - Total Interest Earned: **8M**
  - Total Transaction Amount: **46M**

- Additional insights:
  - **Male customers contributed higher revenue (31M) compared to female customers (26M)**
  - **Blue and Silver credit cards contributed to 93% of total transactions**
  - **TX, NY, and CA states contributed 68% of overall revenue**
  - Overall **activation rate was 57.5%**
  - Overall **delinquent rate was 6.06%**
These insights can help businesses optimize customer targeting and financial strategies.

### Conclusion

This project demonstrates how I used Power BI to transform raw credit card financial data into meaningful and actionable business insights. By applying data modeling, DAX calculations, and interactive visualizations, I developed dashboards that provide a clear view of customer behavior, transaction patterns, and revenue performance. The dashboards enable stakeholders to monitor key metrics, identify high-value customers, and understand spending trends across different categories. Overall, this project highlights the importance of data analytics in supporting strategic decision-making and helping organizations make informed financial decisions.
