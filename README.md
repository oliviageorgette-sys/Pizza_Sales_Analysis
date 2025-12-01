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

## Insights
## Page 1– Pizza Sales Performance Overview
![Page 1](https://github.com/user-attachments/assets/c9a797c0-7e55-47d1-92bb-b90967e030df)

The dashboard opens with a high-level view of the restaurant’s performance. In 2015, the business generated $817K in total revenue from 21,350 orders, selling 49,574 pizzas across all categories and sizes. The restaurant averaged $2,284 in daily revenue and almost 60 orders per day—a strong indicator of consistent customer demand.

Looking across the year, revenue fluctuates with several peaks. January, March, July, and November stand out with higher revenue levels, suggesting effective promotions or higher customer activity during these months. December shows a notable drop, signaling a potential seasonal decline or operational challenge.

When analyzing product categories, Classic pizzas clearly dominate, contributing the highest revenue. Supreme and Chicken categories follow closely, while Veggie pizzas consistently bring in the least revenue. This distribution highlights strong customer preferences for more traditional and meat-based pizza offerings.

A look at specific pizzas shows that the Classic Deluxe Pizza is the top bestseller, followed by other customer favorites such as the Barbecue Chicken Pizza and The Hawaiian Pizza. On the opposite end, pizzas like the Spinach Pesto Pizza and the Mediterranean Pizza show significantly lower sales, forming the list of worst-performing items. These variations help reveal what resonates with customers and what may require rebranding, price adjustments, or removal.

Finally, pizza size distribution shows that Large (L) pizzas dominate customer choices, followed by Medium (M). Extra-large (XL and XXL) sizes contribute minimal revenue, suggesting low demand for oversized portions.

Overall, Page 1 provides a clear snapshot of business performance—strong sales volume, predictable demand patterns, and distinct customer product preferences.
