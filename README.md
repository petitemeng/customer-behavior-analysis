# Customer Shopping Behavior Analysis

## Overview
This project analyzes customer transaction data to uncover purchasing patterns, identify high-value customer segments, and provide data-driven business recommendations.

## Tools Used
- Python (Pandas, NumPy) – Data cleaning
- PostgreSQL – SQL analysis
- Power BI – Dashboard visualization

## Dataset
- 3,900+ transaction records
- Fields: customer demographics, purchase amount, discount, shipping type, etc.

## Key Questions Answered
1. Who are the high-value customer segments?
2. How do discount users behave differently?
3. Which product categories drive the most revenue?

## Files in This Repo
- `sql/customer_analysis.sql` – All SQL queries used
- `notebooks/data_cleaning.ipynb` – Python cleaning steps
- `dashboard/dashboard.pbix` – Power BI file

## Key Insights
- Express-shipping customers have higher lifetime value
- Discount users drive volume but are price-sensitive

## How to Run
1. Clone this repo
2. Import `sql/customer_analysis.sql` into PostgreSQL
3. Open `dashboard.pbix` with Power BI Desktop (Windows only)

## Author
Meng Yu – https://www.linkedin.com/in/meng-y-23a410291

## Acknowledgements
This project was built while following a tutorial. The code was written by me, with additional analysis on customer segments.
