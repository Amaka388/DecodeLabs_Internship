# Week 3: SQL Data Cleaning and Analysis

## Project Description
This project involved importing the dataset into SQL Server Management Studio (SSMS) and performing data cleaning, transformation, and analysis using T-SQL.

## Objectives
- Import and structure the dataset in SQL Server
- Handle missing values and standardize inconsistent data
- Trim whitespace across text columns
- Break down date fields into Year and Month
- Write SELECT, WHERE, ORDER BY, and GROUP BY queries
- Perform aggregations (COUNT, SUM, AVG) to generate business insights

## Tools Used
- Microsoft SQL Server Management Studio (SSMS)
- T-SQL

## Key Insights
- Nearly 41% of all orders end in cancellation or return, while successful delivery accounts for the smallest share of order outcomes — suggesting the company should investigate fulfillment and shipping reliability.
- Chair generated the most revenue among all products but also had the highest cancellation count, warranting further investigation.
- Orders using a coupon far outnumber those without, but average order value is nearly identical between the two groups — suggesting coupons drive order volume more than spend per order.

## Files
- `online_retail_analysis.sql` — full set of cleaning and analysis queries
