# Sales Performance Dashboard Analytics

## 📌 Project Overview

This project analyzes sales performance data using Microsoft Power BI to provide actionable business insights. The dashboard enables stakeholders to monitor revenue trends, customer behavior, product performance, and regional sales distribution, supporting data-driven decision-making.

## 🎯 Business Problem

Organizations often struggle to identify:

- Top-performing products
- High-revenue regions
- Customer purchasing patterns
- Monthly sales trends
- Key factors affecting profitability

This dashboard addresses these challenges by providing interactive visualizations and performance metrics.

---

## 📊 Objectives

The primary objectives of this project are:

- Analyze overall sales performance.
- Identify top-performing products and categories.
- Monitor monthly and yearly revenue trends.
- Evaluate regional sales performance.
- Track customer purchasing behavior.
- Provide management with actionable insights.

---

## 🛠 Tools and Technologies

| Tool | Purpose | Remark |
|--------|---------|-------------|
| Power BI Desktop | Data Visualization & Dashboard Development | Excellent |
| Microsoft Excel | Data Source | Good | 
| Power Query | Data Cleaning & Transformation | Excellent |
| DAX | Calculated Measures and KPIs | Excellent |
| GitHub | Project Documentation & Version Control | Good |

---

## 📂 Dataset Information

The dataset contains transactional sales data with the following fields:

- Order ID
- Order Date
- Customer Name
- Product Category
- Product Name
- Quantity Sold
- Unit Price
- Sales Revenue
- Region
- Profit

### Sample Data Structure

| Order ID | Date | Product | Category | Region | Revenue |
|-----------|---------|----------|----------|----------|----------|
| 1001 | 2024-01-15 | Laptop | Electronics | West | $1,200 |
| 1002 | 2024-01-18 | Printer | Office Supplies | East | $350 |
| 1003 | 2024-01-22 | Monitor | Electronics | South | $500 |

---

## 🔄 Data Cleaning Process

The following transformations were performed using Power Query:

- Removed duplicate records.
- Handled missing values.
- Converted data types.
- Created date hierarchy.
- Standardized column names.
- Added calculated columns for profitability analysis.

---

## 📈 Key Performance Indicators (KPIs)

The dashboard tracks:

- Total Sales Revenue
- Total Profit
- Total Orders
- Average Order Value
- Profit Margin (%)
- Top Product Category
- Best Performing Region

---

## 📊 Dashboard Visualizations

### Executive Summary

- KPI Cards
- Revenue Trend Line Chart
- Profit Trend Analysis

### Sales Analysis

- Monthly Sales Trend
- Product Category Performance
- Top 10 Products by Revenue

### Regional Analysis

- Sales by Region Map
- Revenue by State/Province
- Regional Profitability

### Customer Analysis

- Customer Segmentation
- Top Customers
- Purchase Frequency

---

## 📐 DAX Measures Used

### Total Revenue

```DAX
Total Revenue = SUM(Sales[Revenue])
```

### Total Profit

```DAX
Total Profit = SUM(Sales[Profit])
```

### Profit Margin %

```DAX
Profit Margin % =
DIVIDE([Total Profit], [Total Revenue], 0)
```

### Average Order Value

```DAX
Average Order Value =
DIVIDE([Total Revenue], DISTINCTCOUNT(Sales[Order ID]))
```

---

## 📷 Dashboard Preview

### Executive Dashboard

![Dashboard Screenshot](https://github.com/AfeezTheAnalyst/Sales-Analysis/blob/main/Screenshot%202026-05-17%20172633.png)
![my dashboard]()
### Sales Analysis Dashboard

![Sales Dashboard](https://github.com/AfeezTheAnalyst/Sales-Analysis/blob/main/dash.png)

### Regional Analysis Dashboard

![Regional Dashboard](images/regional_analysis.png)

---

## 🔍 Key Insights

### Revenue Performance

- Total revenue exceeded annual targets by 12%.
- Revenue increased steadily during Q3 and Q4.

### Product Performance

- Electronics generated the highest revenue.
- Office Supplies contributed the highest sales volume.

### Regional Performance

- Western region recorded the highest revenue.
- Southern region showed the highest profit margin.

### Customer Behavior

- 20% of customers generated over 60% of revenue.
- Repeat customers had significantly higher average order values.

---

## 💡 Recommendations

1. Increase inventory for top-performing products.
2. Expand marketing efforts in high-performing regions.
3. Develop customer loyalty programs.
4. Investigate underperforming product categories.
5. Focus on retaining high-value customers.

---

## 📁 Project Structure

```text
PowerBI-Sales-Dashboard/
│
├── data/
│   └── sales_data.xlsx
│
├── dashboard/
│   └── Sales_Dashboard.pbix
│
├── images/
│   ├── dashboard_overview.png
│   ├── sales_analysis.png
│   └── regional_analysis.png
│
├── README.md
│
└── documentation/
    └── project_report.pdf
```

---

## 🚀 How to Use

1. Download the repository.
2. Open the `.pbix` file using Power BI Desktop.
3. Refresh the data source if necessary.
4. Explore the dashboard using filters and slicers.

---

## 📚 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Calculations
- Dashboard Design
- Data Visualization
- Business Intelligence
- Analytical Storytelling

---

## 👨‍💻 Author

**Afeez Akinleye**

Data Analyst | Business Intelligence Enthusiast

GitHub: https://github.com/AfeezTheAnalyst

LinkedIn: Add your LinkedIn profile here

---

## 📄 License

This project is intended for educational and portfolio purposes.
