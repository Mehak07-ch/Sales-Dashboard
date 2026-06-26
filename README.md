[# 📊 Sales Data Analysis Dashboard | Power BI

## 📌 Project Overview

The **Sales Data Analysis Dashboard** is an interactive Business Intelligence project developed using **Power BI** to analyze and visualize sales performance from the Superstore dataset.

This dashboard transforms raw sales data into meaningful insights by tracking sales, profit, product performance, regional performance, and sales trends over time. It demonstrates how organizations use data analytics to make informed business decisions.

## 🎯 Project Objective

The objective of this project is to:

- Analyze overall business performance
- Track sales and profit trends
- Identify top-performing products
- Compare regional performance
- Discover monthly and yearly sales patterns
- Build an interactive dashboard for business users

## 🛠️ Tools & Technologies Used

- Microsoft Power BI
- Microsoft Excel
- CSV Dataset
- Power Query Editor
- DAX (Data Analysis Expressions)

## 📂 Dataset

**Dataset Used:** Sales_Data_Dashboard_Project

### Dataset Includes

- Order ID
- Order Date
- Product 
- Category
- Region
- Sales
- Profit

Source:
- Kaggle Superstore Dataset


# 📋 Project Workflow

## Step 1: Load Dataset

- Imported the CSV file into Power BI.
- Verified column names and data types.
- Checked the dataset structure.

## Step 2: Data Cleaning

Performed data cleaning using Power Query.

Tasks completed:

- Removed duplicate records
- Checked for missing values
- Converted Order Date to Date format
- Corrected incorrect data types
- Removed unnecessary columns
- Verified numerical columns

## Step 3: Data Transformation

Prepared the data for analysis.

Created:

- Month
- Year
- Month-Year
- Profit Margin (if required)

Formatted:

- Currency columns
- Date hierarchy

## Step 4: KPI Analysis

Created Key Performance Indicators.

KPIs include:

- Total Sales
- Total Profit
- Total Orders
- Profit Margin

Example DAX Measures

### Total Sales

```DAX
Total Sales = SUM(Sales_Data_Dashboard_Project[Sales])
```

### Total Profit

```DAX
Total Profit = SUM(Sales_Data_Dashboard_Project[Profit])
```

### Total Orders

```DAX
Total Orders = COUNT(Sales_Data_Dashboard_Project[Order ID])
```

### Profit Margin

```DAX
Profit Margin = 
DIVIDE(
    [Total Profit],
    [Total Sales]
) * 100
```

# 📈 Dashboard Visualizations

The dashboard contains multiple interactive visualizations.

## 1. KPI Cards

Shows:

- Total Sales
- Total Profit
- Total Orders
- Profit Margin

Purpose:

Provides a quick overview of business performance.

---

## 2. Total Profit by Product

Visualization:

Clustered Column Chart

Fields:

- X-Axis → Profit
- Y-Axis → Product

Purpose:

Analyze profit and product growth.

## 3. Total Sales by Month

Visualization:

Line Chart

Fields:

- X-Axis → Month
- Y-Axis → Sales

Purpose:

Analyze sales growth by month.

## 4. Sales by Category

Visualization:

Pie Chart

Fields:

- Legend → Category
- Values → Sales

Purpose:

Compare contribution of each product category.

## 5. Sales by Region

Visualization:

Stacked Bar Chart

Fields:

- Axis → Region
- Values → Sales

Purpose:

Identify highest revenue-generating regions.

## 6. Profit by Product

Visualization:

Bar Chart

Fields:

- Axis → Product
- Values → Profit

Purpose:

Compare profitability across products.

## 7. Top Performing Products

Visualization:

Stacked Bar Chart

Fields:

- Product
- Sales

Purpose:

Identify products generating maximum revenue.

## 8. Sales by Segment

Visualization:

Pie Chart

Purpose:

Compare sales contribution of different customer segments.

## 9. Monthly Sales Analysis

Visualization:

Line Chart

Purpose:

Analyze seasonal sales trends.

## 10. Sales Table

Displays

- Product
- Category
- Sales
- Profit
- Region

Purpose

Detailed transaction analysis.

# 🎛 Dashboard Features

Interactive dashboard with:

- Region Filter
- Category Filter
- Month Slicer

Users can dynamically explore data by selecting different filters.

# 📊 Business Insights

The dashboard helps answer questions such as:

- Which products generate the highest sales?
- Which region contributes the most revenue?
- Which category earns the highest profit?
- How do sales change over time?
- What are the seasonal trends?
- Which products need improvement?
- Which regions perform poorly?

# 📁 Repository Structure

```
Sales-Data-Analysis-Dashboard/
│
├── Dataset/
│   └── Sales_Data_Dashboard_Project.csv
│
├── Dashboard/
│   └── Sales Dashboard.pbix
│
├── Images/
│   ├── Snapshot of Dashboard.png
│
├── README.md
│
└── LICENSE
```

# 📷 Dashboard Preview
```
Images/
    https://github.com/Mehak07-ch/Sales-Dashboard/blob/main/Snapshot%20of%20Dashboard.png
```

# 🚀 Key Learnings

Through this project, I learned:

- Data Cleaning using Power Query
- Data Transformation
- DAX Measures
- KPI Design
- Dashboard Design Principles
- Business Intelligence Reporting
- Interactive Filtering
- Data Visualization Best Practices

# 📈 Future Improvements

Possible enhancements:

- Forecast future sales
- Customer segmentation
- Profit forecasting
- Sales target comparison
- Geographic map visualization
- Drill-through reports
- Mobile-friendly dashboard

# 💼 Skills Demonstrated

- Data Cleaning
- Data Visualization
- Business Intelligence
- Power BI
- Dashboard Development
- DAX
- Power Query
- Excel
- Data Analysis
- Reporting

# ⭐ Project Outcome

This project demonstrates how raw business data can be transformed into meaningful dashboards that support strategic decision-making.

The interactive dashboard enables stakeholders to monitor performance, identify trends, compare regions and products, and make data-driven business decisions efficiently.

## 👩‍💻 Author

**Mehak Chauhan**

Aspiring Data Analyst | Power BI | Excel | SQL | Python

If you found this project helpful, feel free to ⭐ star this repository.
