# baskin-robbins-product-analysis-dashboard
An interactive Power BI dashboard analyzing Baskin Robbins sales performance, product trends, store insights, and YoY growth using DAX and data visualization techniques.

📊 Project Overview

This project presents a Power BI Product Analysis Dashboard built using Baskin Robbins sales data. The dashboard provides insights into total sales, quantity sold, average order value, year-over-year growth, store performance, and category-wise analysis.

The goal of this project is to analyze business performance and help in data-driven decision-making.

🎯 Objectives

Analyze total sales and quantity performance

Track Year-over-Year (YoY) Growth

Identify top-performing categories and products

Analyze payment mode distribution

Compare store performance

Visualize sales distribution by state

📌 Key KPIs

💰 Total Sales: 24.48M

📦 Total Quantity Sold: 150K

🧾 Average Order Value (AOV): 489.56

📈 YoY Growth: 20.37%

🏬 Total Stores: 270

📈 Dashboard Features

1️⃣ Sales Analysis

Total Sales by Year (Trend Analysis)

Year-over-Year Growth Calculation

2️⃣ Category Analysis

Total Sales by Category

Category Contribution %

3️⃣ Product Analysis

Total Quantity by Item Name

Top-Selling Products

4️⃣ Store Analysis

Total Sales by Store Name

Performance Comparison

5️⃣ Payment Mode Analysis

Sales by Payment Type (Cash, Card, UPI, Digital, Gift Card)

6️⃣ Geographic Analysis

Sales by State (Map Visualization)

🛠 Tools & Technologies Used

📊 Power BI

📂 Power Query (Data Cleaning & Transformation)

🧮 DAX (Data Analysis Expressions)

📁 Excel Dataset

🧮 Important DAX Measures Used
Total Sales = SUM(Sales[Sub_total])

Total Quantity = SUM(Sales[Quantity])

AOV = DIVIDE([Total Sales], [Total Quantity])

Sales LY = CALCULATE([Total Sales], SAMEPERIODLASTYEAR(Date[Date]))

YoY Growth = 
DIVIDE([Total Sales] - [Sales LY], [Sales LY])
📂 Dataset Information

The dataset includes:

Order ID

Item Name

Category

Quantity

Rate

Sub Total

Payment Mode

Store Name

Order Date

State

🚀 How to Use

Download the .pbix file from the repository

Open in Power BI Desktop

Explore interactive filters:

Bill Date

Store Name

Category

💡 Business Insights

Identified top-performing product categories

Analyzed high revenue generating stores

Observed strong YoY growth

Understood customer payment preferences

👩‍💻 Author

Shaik Mulinti Sabiha

Aspiring Data Analyst

Power BI | SQL | Data Analytics

⭐ If you like this project

Give it a ⭐ on GitHub and feel free to connect!
