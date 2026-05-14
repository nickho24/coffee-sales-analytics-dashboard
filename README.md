# Coffee Sales Analytics Dashboard

## Overview
This project is an interactive Power BI dashboard built to analyse coffee shop sales performance and product trends. It focuses on key retail metrics such as total sales, total orders, total quantity sold, category performance, store location trends, weekday/weekend behaviour, hourly demand, and product popularity.

The dashboard transforms transaction-level sales data into clear and actionable insights for retail performance monitoring and decision-making.

## Objectives
- Track total sales, orders, and quantity sold over time
- Compare performance across stores, product categories, and product types
- Analyse weekday vs weekend behaviour
- Understand hourly and day-level sales patterns
- Explore product-level popularity and ranking
- Demonstrate predictive and comparative sales analysis using DAX and interactive visuals

## Tools Used
- Power BI
- Power Query
- DAX
- Data Modelling
- Excel data source

## Data Model
The project uses a structured model with:
- **Fact table:** Sales transactions
- **Dimension tables:** Date, Time, Product, Category, Type, Store
- **Measure table:** KPI and business logic measures
- **Parameter tables:** Ranking, Top/Bottom logic, Breakdown selection
- **Prediction table:** Predicted unit price input

This model supports scalability, usability, and reusable reporting logic.

## Key Features
- KPI cards for total sales, total orders, and quantity sold
- Monthly sales overview with daily performance trend
- Weekday vs weekend comparison
- Store location sales analysis
- Product category and product type performance analysis
- Heatmap for sales by day and hour
- Scatter plot with correlation coefficient between unit price and sales
- Word cloud for popular product details
- Top/bottom ranking logic with dynamic breakdown selection
- Custom tooltip pages for date and day-hour insights
- Predicted sales output using linear regression-style logic

## DAX / KPI Examples
The dashboard includes measures such as:
- Total Sales
- Total Orders
- Total Quantity Sold
- Average Sales per Hour
- Previous Month comparison
- Ranking logic for top/bottom categories or types
- Correlation coefficient
- Predicted sales based on selected unit price

## Insights Generated
- Sales can be monitored over time at monthly and daily level
- Store performance differences are visible across locations
- Weekday and weekend patterns provide insight into customer behaviour
- Hour and weekday heatmaps reveal peak transaction periods
- Category and type rankings highlight best and worst performers
- Product detail analysis helps identify popular items and customer preferences
- Predictive analysis demonstrates the relationship between unit price and sales

## Files
- `Coffee Shop Sales.xlsx` – raw dataset
- `Coffee_Sales_Dashboard.pbix` – Power BI report file
- `screenshots/` – dashboard screenshots
- `README.md` – project documentation

## Screenshots
Include screenshots of:
- Monthly Sales page
- Product Report page
- Data Model
- Calendar Tooltip
- Day and Hour Tooltip

## Project Value
This project demonstrates practical skills in:
- Power BI dashboard development
- DAX measure creation
- Star-schema data modelling
- Retail sales analytics
- Tooltip page design
- Dynamic ranking logic
- Predictive visualisation
- Insight communication