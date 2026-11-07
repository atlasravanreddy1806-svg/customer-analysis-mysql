# Customer Analysis & Segmentation Using MySQL

## Project Overview

This project analyzes customer purchasing behavior using MySQL.

The objective is to understand customer spending, purchase frequency,
retention, customer value, city-level performance, and monthly trends.

The project uses a synthetic dataset containing 30 customers and 65 orders.

## Business Questions

- Who are the highest-value customers?
- What percentage of customers are repeat purchasers?
- How many customers are one-time buyers?
- Which cities generate the most spending?
- What is the average order value?
- How does customer spending change over time?
- How concentrated is spending among top customers?
- Which customer segments represent the biggest opportunity?

## Tools & Technologies

- MySQL
- MySQL Workbench
- SQL
- Git
- GitHub

## SQL Concepts Used

- SELECT
- WHERE
- GROUP BY
- HAVING
- JOIN
- LEFT JOIN
- CASE
- COALESCE
- CTEs
- Aggregate functions
- Window functions
- LAG()
- RANK()
- Date functions
- Conditional aggregation

## Dataset

- 30 customers
- 65 orders
- 61 completed orders
- 2 cancelled orders
- 2 returned orders
- Date range: February 2024 – October 2025
- Dataset type: Synthetic practice data

## Key Insights

### Customer Retention

46.67% of customers are repeat customers.

### Customer Value

6 high-value repeat customers generated ₹91,673 in completed spending.

### One-Time Customers

14 customers made only one completed purchase.

### Average Order Value

Overall AOV is ₹2,420.31.

### City Performance

Hyderabad generated the highest completed spending at ₹60,279.

### Customer Concentration

The top 5 customers contributed 54.17% of completed spending.

### Monthly Trends

June 2025 had the strongest month-over-month growth at 94.89%.

April 2024 recorded the largest decline at -62.51%.

## Business Recommendations

1. Focus on converting one-time customers into repeat customers.
2. Develop loyalty strategies for high-value customers.
3. Increase order value among low-value repeat customers.
4. Investigate cancelled and returned orders.
5. Monitor dependence on a small group of high-value customers.

## Project Structure

customer-analysis-mysql/
│
├── README.md
├── sql/
│   ├── 01_create_database.sql
│   ├── 02_insert_sample_data.sql
│   ├── 03_data_quality_checks.sql
│   ├── 04_customer_analysis.sql
│   ├── 05_city_analysis.sql
│   ├── 06_monthly_analysis.sql
│   ├── 07_retention_analysis.sql
│   └── 08_customer_segmentation.sql
│
└── results/
    └── analysis_findings.md