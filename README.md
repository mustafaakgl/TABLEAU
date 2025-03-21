Retail Data Visualization Projects
Overview
This repository contains two comprehensive retail data visualization projects using Tableau:

"Visualizations of Retail American Company" - Analysis of U.S. retail operations
"Designing Sales Dashboard of Europe Sales of Company" - Analysis of European sales data

Both projects demonstrate how data visualization can transform raw retail data into actionable business insights through effective dashboard design and strategic KPI implementation.
Project 1: Visualizations of Retail American Company
Purpose
This project analyzes U.S. retail sales data to optimize company performance through data-driven decision making. The visualizations help stakeholders understand customer behavior, product performance, and regional sales patterns.
Data Source
The project utilizes the Superstore Global Dataset, available at: https://github.com/jarrodtky/Superstore_Global_Visualization_Tableau/blob/main/Superstore-Global_Dataset.xls
Key Metrics and Calculation Fields

Profit per Order: Total Profit / Total Orders
Return Rate: (Number of return orders) / (Total Orders) * 100
Profit Margin: (Profit / Sales) * 100
Sales per Customer: Total Sales / Number of Unique Customers
Average Order Value: Total Sales / Number of orders
Shipping Duration: DATEDIFF('day', [Order Date], [Ship Date])

Implemented Visualizations

Sales and Profit by Customer Segments
Sales and Profit by Product Segments
Cumulative Sales and Profit
Discount Effectiveness Analysis
Sales Performance Heatmap
Top Cities by Sales and Profit
Customer Lifetime Value Analysis

Dashboard Features

Profit Range Per Order Filter
Shipping Duration Filter
Category/Sub-Category Filter
Customer Lifetime Value Filter
Customer Segmentation Filter

Project 2: Designing Sales Dashboard of Europe Sales of Company
Purpose
This project focuses on European sales data visualization to improve sales performance, optimize inventory management, and develop targeted marketing strategies.
Data Source
The project uses the Europe Sales Records dataset: https://www.kaggle.com/datasets/mustafabayar/europe-sales-records
Key Performance Indicators (KPIs)

Sales Conversion Rate
Return on Investment (ROI) for Marketing Analysis
Net Profit Margin
Sales per Customer
Sales by Product Segment
Regional Sales Analysis (Daily/Weekly/Monthly)

Implemented Visualizations

Profit Margin by Country
Revenue by Item Type
Yearly Sales Trend by Category
Product Margin per Item Type
Regional Sales Distribution Maps

Analytical Insights

Higher profit margins in countries like Andorra and Russia suggest potential for targeted marketing
Baby food category demonstrated exceptional profitability
Fruit category showed poor performance, indicating need for strategic review
Seasonal product trends visible through annual sales analysis

Business Intelligence Application
The project demonstrates how Tableau can help business users make vital decisions around:

Cost reduction opportunities
Revenue growth strategies
Inventory optimization
Customer targeting and segmentation

Technical Implementation
Both projects leverage Tableau's capabilities for:

Data transformation and cleaning
Calculation field creation
Advanced filtering and parameter usage
Interactive dashboard design
Time-series analysis and forecasting
