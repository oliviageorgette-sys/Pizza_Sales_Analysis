# Pizza_Sales_Analysis
Comprehensive Pizza Sales Analytics using Power BI

## Overview

This project delivers an end-to-end analysis of a pizza restaurant’s 2015 sales performance using Power BI.
The goal was to uncover sales trends, customer behavior patterns, order dynamics, and revenue performance across multiple dimensions such as pizza categories, sizes, order types, and time periods.

Through interactive dashboards, this analysis provides clear insights into what drives the restaurant’s performance — revealing best-selling products, customer ordering habits, and opportunities for revenue growth.

## Project Objectives

- Understand overall sales performance and identify key revenue drivers.

- Examine customer behavior, ordering patterns, and product preferences.
- Compare single-pizza vs. multi-pizza order performance.
- Identify best-selling and worst-selling pizzas to guide menu and marketing decisions.
- Provide actionable recommendations to improve sales strategy and operational efficiency.

## Dataset Overview

- Source: Pizza Sales Dataset (2015)
- Total Records: 21,350 Orders
- Key Fields:
* Orders: order_id, order_date, quantity, unit_price
* Pizza Info: category, size, name
* Time-based fields: day of week, month, hour
* Derived fields: revenue, order type (single vs multi)

## Data Preparation & Cleaning

The dataset was cleaned and transformed in Power Query, ensuring high data quality:
- Checked for missing values, duplicates, and incorrect formatting.
- Standardized date formats and created time intelligence fields (month, hour, weekday).
- Created calculated columns such as Order Type (Single vs Multi).
- Built DAX measures for:
* Total Revenue
* Total Orders
* Average Daily Revenue
* Average Order Value (AOV)
* Pizzas per Order
* Multi-Pizza Order Percentage
* Category & size distributions

After cleaning, the dataset was modeled and used to build four dashboard pages
