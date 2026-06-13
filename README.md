📊 EDA — E-Commerce Profit & Sales Analysis

Interactive Power BI Dashboard for Exploratory Data Analysis on E-Commerce Sales Data

 Project Overview

This project performs an end-to-end Exploratory Data Analysis (EDA) on a real-world e-commerce dataset to uncover key business insights around sales performance, profit trends, product categories, and regional patterns.

The final output is an interactive Power BI dashboard that enables business stakeholders to make data-driven decisions by visualizing KPIs and filtering data dynamically across 4 regions — East, North, South, and West.


🎯 Objectives


Track overall business KPIs — Total Sales, Quantity, Profit, and Averages
Analyze monthly Sales vs Profit trends to detect seasonality
Compare regional performance across East, North, South, and West
Understand category-wise profit and sales distribution
Provide actionable insights through an interactive, filterable dashboard



📊 Dashboard Overview

🔢 KPI Cards (Overall)

MetricValueTotal Sales11MTotal Quantity17KTotal Profit2MAverage Sales3,048Average Profit527

📍 Regional Breakdown (via Slicer)

RegionTotal SalesTotal ProfitAvg SalesAvg ProfitEast3M465K3,107540North2M426K2,901497South3M458K3,012519West3M495K3,168552


West region leads in both Total Profit and Average Profit. North region has the lowest sales and profit.




📈 Visuals in Dashboard

VisualDescriptionKPI CardsTotal Sales, Quantity, Profit, Avg Sales, Avg ProfitSum of Sales/Profit by MonthDual line chart — monthly trend comparisonTotal Profit/Sales by RegionClustered bar chart — East, North, South, WestSUM Quantity by CategoryPie chart — High (47%), Low (20.46%), Medium (32.51%)Category wise Profit/SalesHorizontal bar chart — High, Medium, Low categoriesSum of Sales by CategoryDonut chart — LOW dominates at 65.45% of salesRegion SlicerInteractive filter — East / North / South / West


💡 Key Insights


🏆 West region has the highest average profit (552) and total profit (495K)
📉 North region underperforms with lowest sales (2M) and profit (426K)
🛒 LOW category dominates sales volume at 65.45% of total sales
📦 HIGH category leads in quantity share at 47% of total quantity
📅 Monthly trend shows profit remains flat while sales fluctuate — margin pressure exists
🔁 Dashboard is fully interactive — all visuals update dynamically on region filter



🔧 Tools & Technologies

ToolUsagePower BI DesktopDashboard creation, DAX measures, interactive slicersPython (Pandas, NumPy)Data cleaning and preprocessingMatplotlib & SeabornEDA charts and statistical visualizationsMicrosoft ExcelInitial data inspection


🗂️ Dataset

Key Columns:


Order ID, Order Date, Ship Date
Customer Name, Region, City, State
Category, Sub-Category, Product Name
Sales, Quantity, Discount, Profit



📁 Project Structure

eda---ecommerce-profit-and-sales-analysis-/
│
├── ecommerce_sales_data (2).csv   # Raw dataset
├── output_processed.csv           # Cleaned dataset
├── ED PROJRCT DASHBOARD.pbix      # Power BI dashboard file
└── README.md                      # Project documentation


🚀 How to Run


Clone or download this repository
Open ED PROJRCT DASHBOARD.pbix in Power BI Desktop
If prompted, update the data source path to output_processed.csv
Refresh the data and explore the dashboard
Use the East / North / South / West slicer to filter by region
