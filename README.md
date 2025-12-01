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
## Page 1 – Pizza Sales Performance Overview
![Page 1](https://github.com/user-attachments/assets/c9a797c0-7e55-47d1-92bb-b90967e030df)

The dashboard opens with a high-level view of the restaurant’s performance. In 2015, the business generated $817K in total revenue from 21,350 orders, selling 49,574 pizzas across all categories and sizes. The restaurant averaged $2,284 in daily revenue and almost 60 orders per day—a strong indicator of consistent customer demand.

Looking across the year, revenue fluctuates with several peaks. January, March, July, and November stand out with higher revenue levels, suggesting effective promotions or higher customer activity during these months. December shows a notable drop, signaling a potential seasonal decline or operational challenge.

When analyzing product categories, Classic pizzas clearly dominate, contributing the highest revenue. Supreme and Chicken categories follow closely, while Veggie pizzas consistently bring in the least revenue. This distribution highlights strong customer preferences for more traditional and meat-based pizza offerings.

A look at specific pizzas shows that the Classic Deluxe Pizza is the most ordered pizza, followed by other customer favorites such as the Barbecue Chicken Pizza and The Hawaiian Pizza. On the opposite end, pizzas like the Spinach Pesto Pizza and the Mediterranean Pizza are the least ordered pizzas, forming the list of worst-performing items. These variations help reveal what resonates with customers and what may require rebranding, price adjustments, or removal.

Finally, pizza size distribution shows that Large (L) pizzas dominate customer choices, followed by Medium (M). Extra-large (XL and XXL) sizes contribute minimal revenue, suggesting low demand for oversized portions.

Overall, Page 1 provides a clear snapshot of business performance—strong sales volume, predictable demand patterns, and distinct customer product preferences.

## Page 2 
![Page 2](https://github.com/user-attachments/assets/5c9fd1e3-815f-4f96-9410-bb6cf07f0855)

Page 2 dives deeper into how customers behave when ordering pizza. On average, customers purchase 2.32 pizzas per order, and 62% of all orders are multi-pizza orders—showing that customers often buy for groups, families, or events. The Average Unit Price sits at $16.49, while the Average Order Value (AOV) stands at $38.31, confirming that multi-item ordering significantly boosts revenue.

Peak ordering hours provide insight into when demand is highest throughout the day. As expected, 12PM - 1PM (lunch rush) and 5PM - 6PM (early dinner) are the busiest times. These peaks reflect typical eating behavior and help the restaurant optimize staffing and inventory during high-demand periods.

Weekly patterns remain consistent, with Friday and Saturday showing the highest order volumes. This aligns with social behavior as people tend to enjoy convenience foods during weekends. Sunday sees a drop, which may indicate reduced dining activity or opportunities for new Sunday-focused promotions.

The AOV trend fluctuates month-to-month. February and September record slightly higher values, influenced by multi-pizza orders or promotional effects. Although AOV stays relatively stable overall, these variations highlight opportunities to drive higher basket sizes during weaker months.

Finally, the 100% stacked chart provides insight into pizza size preferences within each category. Large pizzas hold the largest share across categories, especially in Chicken and Veggie categories. Meanwhile, XL and XXL pizzas contribute little across all categories, reaffirming their low demand.

Page 2 provides a deep understanding of how customers shop—when they buy, what they choose, and how much they typically spend—helping shape future marketing, pricing, and operational strategies.

## Page 3 – Single vs Multi-Order Insights
![Page 3](https://github.com/user-attachments/assets/20e921df-4009-45aa-9cf2-a5754d5a9c37)

This page focuses specifically on comparing single-pizza and multi-pizza orders. Out of all orders, 13,239 were multi-pizza orders, while 8,111 were single-pizza orders. This confirms that multi-order customers form the majority and are the primary drivers of business revenue.

When looking at the proportion, multi-pizza orders account for 62% of all transactions, while single-pizza orders make up 38%. This difference is reinforced when revenue contribution is analyzed: multi-pizza orders generate an impressive $683K in revenue, compared to $133K from single-pizza orders. Clearly, customers purchasing multiple pizzas are significantly more valuable.

Order volume by hour further highlights behavior differences. Multi-order volumes rise sharply during dinner hours, while single orders rises in lunch hours and remain steady but lower throughout the day. This reinforces the idea that multi-orders are often group-based, event-driven, or family-oriented.

Category preferences also reveal interesting patterns. For every category (Classic, Supreme, Veggie, Chicken), multi-pizza orders dominate with around 83% share, leaving single orders with about 16%. This consistency shows that category preference is not tied to order type—customers across all categories prefer ordering more than one pizza at a time.

Overall, Page 3 makes it clear that multi-pizza orders are the backbone of the business, contributing heavily to revenue and overall sales volume.

## Page 4 – Revenue Insights
![Page 4](https://github.com/user-attachments/assets/d211b2d2-c1dc-4b28-8147-e4a8e4ad32b9)

The final dashboard page zooms into revenue performance, breaking it down by order type and individual pizza products. Monthly revenue trends show that multi-pizza orders generate significantly higher revenue every month. Single-pizza revenue remains stable but low, while multi-pizza revenue shows expected seasonal fluctuations.

The ranking visuals provide further clarity. The Top 10 Revenue-Generating Pizzas list highlights familiar favorites such as The Thai Chicken Pizza, The Barbecue Chicken Pizza, and The California Chicken Pizza—all strong performers with consistent demand.

On the other hand, the Worst 5 Revenue-Generating Pizzas show items with very low sales volume and revenue contributions. These include pizzas like The Spinach Pesto Pizza and The Mediterranean Pizza, which continue to underperform across all metrics.

This final page reinforces earlier insights by making revenue impact clear and ranking products by financial contribution.

## Recommendations

- Strengthen marketing for high-performing pizzas, especially Classic Deluxe, Thai Chicken, and Barbecue Chicken.

- Improve or reconsider low-performing pizzas such as Spinach Pesto and Mediterranean options.

- Launch targeted promotions during non-peak hours and slower months to boost demand.

- Expand meal bundles aligned with the high rate of multi-pizza orders.

- Optimize inventory and staffing for peak periods—12 PM and 5 PM, plus Fridays and Saturdays.

- Reduce focus on XL and XXL pizzas, as demand is consistently low.

## Conclusion 
This analysis provides a complete view of the restaurant’s sales ecosystem — from what customers prefer, to how they behave, to which products drive profitability. With actionable insights and clear patterns, the restaurant is better positioned to make data-driven decisions that improve sales, enhance customer experience, and strengthen operational efficiency.

## Feedback
If you have any suggestions, improvements, or questions about this project, feel free to share them.
I'm continuously learning and open to all constructive feedback to help improve my work.

## Connect With Me
If you'd like to connect or discuss data analytics, Power Bi, or future projects:
- LinkedIn:
- Email: olivia.georgette@gmail.com
- GitHub: 

