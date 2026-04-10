🍕 Pizza Sales Analytics Dashboard

📌 Overview

Designed an interactive Pizza Sales Dashboard using Power BI to analyze sales performance, customer behavior, and product trends.

This project transforms raw transactional data into actionable insights, enabling businesses to optimize menu offerings, improve sales strategies, and make data-driven decisions.

🚨 Business Problem

Food businesses often lack clarity on:

   * Top-performing and underperforming products
   * Customer ordering behavior
   * Peak sales periods
   * Revenue distribution across categories and sizes

This results in inefficient inventory planning, missed revenue opportunities, and suboptimal decision-making.

🎯 Project Objectives
   * Analyze overall sales performance using key KPIs
   * Identify best and worst-selling pizzas
   * Understand daily and monthly sales trends
   * Evaluate performance by category and size
   * Provide actionable insights for business growth

🛠️ Tech Stack
   * Power BI Desktop – Data visualization & dashboard development
   * Power Query – Data cleaning and transformation
   * DAX (Data Analysis Expressions) – KPI calculations
   * Data Modeling – Relationship building & filtering
   * SQL (MySQL) – KPI validation & analytical queries

📂 Dataset Information
   * Dataset: Pizza Sales Data
   * Records: 48,000+ rows
   * Type: Transaction-level data

Key Fields
   * Order ID
   * Pizza Name
   * Quantity
   * Order Date & Time
   * Unit Price
   * Total Price
   * Pizza Size
   * Pizza Category
     
📊 Key KPIs
   * Total Revenue: 817.86K
   * Total Orders: 21,350
   * Total Pizzas Sold: 49,574
   * Average Order Value: 38.31
   * Average Pizzas per Order: 2.32

📈 Dashboard Insights
🔹 Sales Performance
   * Consistent revenue with strong order volume
   * Customers order 2+ pizzas per transaction, indicating bundle behavior
🔹 Best & Worst Sellers
   * Top Revenue Generator: Thai Chicken Pizza
   * Top Quantity Seller: Classic Deluxe Pizza
   * Lowest Performer: Brie Carre Pizza
🔹 Daily Trends
   * Peak orders on Friday & Saturday evenings
   * Weekends outperform weekdays
🔹 Monthly Trends
   * Highest sales in January & July
   * Lower performance in October & December
🔹 Category Insights
   * Classic category contributes the highest revenue share
🔹 Size Insights
   * Large pizzas generate the most revenue

     
⭐ Project Highlights
   * Built an interactive dashboard analyzing 48K+ records
   * Developed dynamic KPIs using DAX
   * Identified key revenue drivers and underperforming products
   * Analyzed customer behavior across time and product dimensions
   * Enabled data-driven decision-making

🚀 Recommendations
   * Promote top-performing pizzas to maximize revenue
   * Improve or replace low-performing items
   * Optimize staffing and inventory for weekend peaks
   * Introduce combo offers to leverage high order volume
   * Focus on large-size promotions for higher revenue

🗄️ SQL Analysis (KPI Validation & Insights)

Although the dashboard was built in Power BI, SQL queries were developed to validate KPIs and perform additional analysis.

🔹 Sample KPI Queries

-- Total Revenue
SELECT ROUND(SUM(total_price), 2) AS total_revenue
FROM pizza_sales;


-- Total Orders
SELECT COUNT(DISTINCT order_id) AS total_orders
FROM pizza_sales;


-- Average Order Value
SELECT ROUND(SUM(total_price) / COUNT(DISTINCT order_id), 2) AS avg_order_value
FROM pizza_sales;

📊 Business Impact
   * Improved visibility into sales performance
   * Enabled better inventory and demand planning
   * Supported targeted marketing strategies
   * Helped identify high and low-performing products

     
🎯 Use Cases
   * Business Owners: Revenue optimization
   * Operations Teams: Demand forecasting
   * Marketing Teams: Product promotion strategy
   * Data Analysts: End-to-end analytics project

✅ Conclusion

This dashboard provides a comprehensive analysis of pizza sales, helping businesses make informed decisions, improve profitability, and enhance customer satisfaction through data-driven insights.
