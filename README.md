# Sales-Analysis-Report-Dashboard
📊 Power BI Sales Performance Dashboard
📘 Project Overview

This project presents a Sales Performance Dashboard built in Microsoft Power BI, designed to analyze sales data and provide actionable insights into key performance metrics such as total sales, order volume, freight cost, and regional performance.

The dashboard enables interactive exploration through hierarchies, slicers, and dynamic visuals — helping stakeholders make data-driven business decisions with confidence.

🧩 Data Modeling

Star Schema design for optimized relationships between Fact and Dimension tables.

Product Hierarchy established to allow drill-down analysis:

Category → SubCategory → Product

Tables Used:

FactSales (Sales transactions)

DimProduct (Product details)

DimCustomer (Customer demographics)

DimTerritory (Geographical data)

DimDate (Date intelligence)

🧮 Key Measures (DAX)

# Orders = COUNT(SalesFact[OrderID])

# Order Details = COUNT(SalesFact[OrderDetailID])

Total SubTotal = SUM(SalesFact[SubTotal])

Total Tax = SUM(SalesFact[TaxAmt])

Total Freight = SUM(SalesFact[Freight])

Total Due = SUM(SalesFact[TotalDue])

Each measure was formatted and rounded for professional presentation, supporting analysis at different granularity levels.

📈 Visuals & Insights

The report includes a combination of KPIs, charts, and filters for comprehensive analysis:

Visuals:

KPI Cards: Orders, SubTotal, Tax, Freight, Total Due

Line Chart: Orders by Order Date

Bar Chart: Orders by Status

Treemap: Order Quantity by Category, SubCategory, Product

Combo Chart: Orders vs. Total Due by Territory

Slicers: Category, Year, and Status

Design Focus:

Clear and consistent layout

Rounded visuals for modern UI

Professional color palette

Meaningful chart titles and tooltips

📊 Performance Highlights

💰 $30.1M Total Sales

📦 1,465 Orders Processed

🚚 $916K Freight Managed

💵 $33.9M Total Due

Top Insights:

Peak performance in 2013 with record-high order volume.

North America led in revenue contribution (≈58%).

Technology category dominated overall sales.

Over 6.4K approved orders, reflecting operational efficiency.

💡 Tools & Technologies

Microsoft Power BI

DAX (Data Analysis Expressions)

Data Modeling (Star Schema)

ETL in Power Query

Excel / SQL Source Integration

🏷️ Tags
#PowerBI #DataAnalytics #SalesDashboard #BusinessIntelligence #DAX #DataVisualization
