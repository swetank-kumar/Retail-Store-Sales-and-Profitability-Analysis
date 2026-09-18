# Retail Store Sales & Profitability Analysis 📊
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/swetank-jha)

## What this project is about
The store's sales were growing, but profit wasn't growing at the same pace. This project analyzes ~10,000 retail transactions to understand where profit was being generated, where losses were occurring, and how discounts and product categories affected profitability.

I used SQL to clean and prepare the data and Power BI to build an interactive dashboard for analyzing sales and profitability.

## Tools I used
- **MySQL** — data cleaning, transformation, and preparation
- **SQL** — filtering, joins, grouping, aggregations, and basic calculations
- **Power BI** — interactive dashboard and reporting
- **DAX** — KPI calculations and year-over-year growth analysis

## What I did

### 1. Cleaned the data in SQL
- Fixed inconsistent date formats
- Corrected columns stored as text instead of numbers
- Checked for missing and inconsistent values
- Standardized data before using it for reporting

### 2. Created calculated fields
I created additional fields to support the analysis, including:
- Profit Margin %
- Profit/Loss/Neutral order status
- Unit-level calculations used for profitability analysis

### 3. Organized the data for Power BI
Instead of keeping everything in one large table, I organized the data into connected tables for:
- Customers
- Products
- Locations
- Dates
- Sales transactions

This follows a simple approach — one main sales table linked to smaller tables like customers, products, and dates and makes the Power BI model easier to manage and analyze.

### 4. Built the Power BI dashboard
The dashboard contains two main pages focused on overall performance and profitability.

## Dashboard Pages

### Page 1: Overview
A high-level view of business performance, including:
- Total Sales
- Total Profit
- Number of Orders
- Average Order Value
- Year-over-Year Growth
- Regional performance
- Sales and profit trends

### Page 2: Where the losses are coming from
A detailed view focused on profitability, including:
- Relationship between discounts and profit
- Product/category profitability
- Loss-making orders
- Customers and their contribution to revenue and profit

## What I found
- **Discounting pattern:** In this dataset, discounts above approximately 20% were frequently associated with negative profitability across many categories.
- **Product mix:** Tables and Bookcases were among the major loss-making areas, particularly when sold at higher discounts.
- **Loss-making orders:** Approximately 19% of orders in the dataset were classified as loss-making.

## What I'd suggest based on this analysis
1. Review or require additional approval for higher discounts, particularly around the 15–20% range.
2. Review pricing or bundling strategies for loss-making product categories such as Tables and Bookcases.
3. Track the percentage of loss-making orders as a regular business KPI.
4. Monitor profitability alongside sales growth rather than relying on revenue alone.

## Dashboard Screenshots

### Overview
![Executive Dashboard](./Visuals/1.Overview.png)

### Where the losses are coming from
![Profitability Diagnostics](./Visuals/2.Details.png)

👤 **Author:** Swetank Kumar Jha ([LinkedIn](https://www.linkedin.com/in/swetank-jha))
