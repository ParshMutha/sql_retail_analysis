RETAIL SALES ANALYSIS USING SQL

PROJECT OVERVIEW
This project focuses on data cleaning, exploration, and analysis of a retail sales dataset using SQL.
The objective is to extract meaningful business insights such as customer behavior, category-wise sales performance, and monthly sales trends.

This project demonstrates practical SQL skills including:
- Data cleaning and handling NULL values
- Data aggregation and grouping
- Date-based analysis
- Filtering and sorting data
- Business-oriented analytical queries


DATASET DESCRIPTION
The dataset contains retail sales transaction data with the following columns:

transactions_id   : Unique transaction identifier
sale_date         : Date of the sale
sale_time         : Time of the sale
customer_id       : Unique customer ID
gender            : Gender of the customer
age               : Age of the customer
category          : Product category
quantity          : Quantity sold
price_per_unit    : Price per unit
cogs              : Cost of goods sold
total_sale        : Total sale amount


DATA CLEANING PROCESS
The following data cleaning steps were performed:

- Identified NULL values across all important columns
- Removed records containing NULL values
- Ensured data consistency before analysis
- Verified distinct customers and categories


EXPLORATORY DATA ANALYSIS

1. Retrieved all sales made on a specific date (2022-11-05)
2. Filtered Clothing category transactions with high quantity sales in November 2022
3. Calculated total sales for each product category
4. Identified transactions with total sale value greater than 1000
5. Analyzed transaction count by gender and category
6. Found top 5 customers based on highest total sales
7. Calculated unique customers per category
8. Analyzed average monthly sales and best-selling months


KEY INSIGHTS
- Certain categories generate higher revenue
- A small group of customers contributes significantly to total sales
- Monthly and seasonal trends are visible in sales data
- Gender-based purchasing behavior varies across categories



TOOLS AND TECHNOLOGIES USED
- SQL (PostgreSQL compatible)
- Aggregate functions: SUM, COUNT, AVG
- Date functions: EXTRACT, TO_CHAR


PROJECT STRUCTURE

Retail-Sales-SQL-Analysis
|-- README.txt
|-- retail_sales.sql
|-- retail_sales_dataset.csv


AUTHOR
Parsh Mutha
India
Aspiring Data Analyst
