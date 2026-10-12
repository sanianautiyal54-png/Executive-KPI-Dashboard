📊 Executive KPI Dashboard – Power BI

📌 Project Overview

The Executive KPI Dashboard is an interactive business intelligence dashboard developed using Microsoft Power BI. It analyzes Superstore sales data to provide insights into sales performance, profitability, order volume, and product categories.

The dashboard helps users monitor key performance indicators (KPIs) and explore business performance using interactive filters and visualizations.

🎯 Project Objectives

- Analyze overall sales and profit performance.
- Track total orders and quantity sold.
- Monitor profit margin percentage.
- Compare sales across product categories and sub-categories.
- Explore business performance by year, region, category, and customer segment.
- Present business data in a clear, interactive, one-page dashboard.

🛠️ Tools & Technologies

- Microsoft Power BI Desktop – Dashboard development and data visualization
- Microsoft Excel – Dataset source
- DAX (Data Analysis Expressions) – KPI calculations and measures
- GitHub – Project documentation and portfolio

📂 Dataset

This project uses the Superstore dataset, which contains information about orders, customers, products, sales, discounts, and profits.

Key fields include:

- Order Date and Ship Date
- Customer Segment
- Region, State, and City
- Product Category and Sub-Category
- Sales and Quantity
- Discount and Profit

📈 Key Performance Indicators (KPIs)

The dashboard includes five main KPIs:

1. Total Sales
2. Total Profit
3. Total Orders
4. Total Quantity
5. Profit Margin (%)

📖 KPI Definitions and Calculations

KPI| Definition| Calculation
Total Sales| Total revenue generated from orders.| Sum of Sales
Total Profit| Total profit earned from orders.| Sum of Profit
Total Orders| Number of unique orders placed.| Distinct count of Order ID
Total Quantity| Total units of products sold.| Sum of Quantity
Profit Margin (%)| Percentage of sales revenue retained as profit.| (Total Profit ÷ Total Sales) × 100

DAX Measures

The following DAX measures can be used to calculate the KPIs in Power BI:

Total Sales = SUM('Superstore'[Sales])

Total Profit = SUM('Superstore'[Profit])

Total Orders = DISTINCTCOUNT('Superstore'[Order ID])

Total Quantity = SUM('Superstore'[Quantity])

Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

Note: Format the "Profit Margin %" measure as a percentage in Power BI. These measures respond to report filters when the model relationships and visual interactions are configured correctly.

📊 Dashboard Visualizations

The dashboard includes:

- Treemap: Sales by Sub-Category
- Donut Chart: Sales by Category
- Waterfall Chart: Profit Contribution
- KPI Cards: Summary of important business metrics
- Interactive Slicers: Year, Region, Category, and Segment

🎛️ Interactive Features

Users can filter the dashboard by:

- Year
- Region
- Product Category
- Customer Segment

These slicers allow users to explore different aspects of business performance dynamically.

💡 Business Insights

The dashboard can help users:

- Compare sales performance across product categories.
- Identify product groups contributing to profit or loss.
- Explore differences in performance across regions.
- Understand how KPIs change by year and customer segment.

Add specific findings after reviewing the actual results displayed in your dashboard.


📁 Project Files

- "Executive KPI Dashboard.pbix" – Power BI dashboard file
- "dashboard-screenshot.png" – Dashboard preview image
- "README.md" – Project documentation



---

⭐ If you find this project useful, feel free to explore the dashboard and its visualizations.
