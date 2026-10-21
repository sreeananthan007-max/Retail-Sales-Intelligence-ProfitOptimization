# Retail-Sales-Intelligence-ProfitOptimization

## Project Overview

This project analyzes retail sales data to understand sales performance, profitability, discount patterns, regional performance, and customer segments.

The main purpose of the project is to identify factors associated with low profitability and provide data-driven recommendations that can help improve profit margins.

The project was completed using Python and Excel.

---

## Business Objectives

1. Identify the most profitable and least profitable product categories.
2. Analyze monthly and yearly sales and profit trends.
3. Investigate the relationship between discounts, sales, and profit.
4. Identify regions and customer segments contributing the most and least profit.
5. Identify products generating high sales but low or negative profit.
6. Provide data-driven recommendations to improve profitability.

---

## Tools Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Microsoft Excel
- Jupyter Notebook

---

## Dataset

The project uses the Sample Superstore retail dataset.

The dataset contains information such as:

- Order Date
- Product Name
- Category
- Sales
- Quantity
- Discount
- Profit
- Customer Segment
- Region

### Data Quality

The original dataset was checked for:

- Missing values
- Duplicate records
- Data types

The dataset did not contain any missing values or duplicate records.

Therefore, no removal or replacement of missing values and no duplicate removal were required.

The `Order Date` column was converted to datetime format to support time-based analysis.

Two new features were created:

- `Year`
- `Month`

These features were used to analyze yearly and monthly sales and profit trends.

---

## Data Analysis

### 1. Category Analysis

Sales and profit were grouped by product category to identify the most and least profitable categories.

### 2. Sales and Profit Trends

Yearly and monthly sales and profit were analyzed to understand changes in business performance over time.

### 3. Discount Analysis

The relationship between discount, sales, and profit was investigated using correlation and visual analysis.

Correlation was used to identify relationships between variables and was not interpreted as proof of causation.

### 4. Regional Analysis

Profit was analyzed across different regions to identify the highest and lowest profit-contributing regions.

### 5. Customer Segment Analysis

Customer segments were compared based on their contribution to overall profit.

### 6. Product Analysis

Products were analyzed based on total sales and profit to identify high-sales products generating negative profit.

---

## Data Visualization

Matplotlib and Seaborn were used to create visualizations including:

- Profit by Category
- Yearly Sales and Profit Trend
- Monthly Sales and Profit Trend
- Discount vs Profit
- Discount vs Sales
- Correlation Heatmap
- Profit by Region
- Profit by Customer Segment
- High-Sales Products with Negative Profit
- Profit Distribution

---

## Excel Dashboard

An interactive Excel dashboard was created to present the major business insights.

### KPI Cards

- Total Sales
- Total Profit
- Average Discount

### Dashboard Charts

- Profit by Category
- Monthly Sales Trend
- Profit by Region
- Profit by Customer Segment

### Interactive Slicers

- Year
- Region
- Category
- Segment

The dashboard uses a dark theme and allows users to interactively explore retail performance.

---

## Key Findings

The analysis identifies:

- Differences in profitability across product categories.
- Changes in sales and profit over time.
- Relationships between discount levels and profitability.
- Differences in profit contribution across regions.
- Differences in profitability across customer segments.
- High-sales products that still generate negative profit.

The exact findings and values are based on the results generated from the analysis and dashboard.

---

## Business Recommendations

1. Review discount strategies, especially where higher discounts are associated with weaker profitability.
2. Focus on improving the performance of low-profit categories, regions, and customer segments.
3. Investigate high-sales products generating negative profit to determine whether pricing, discounting, or other factors are reducing profitability.
4. Continue monitoring monthly and yearly sales and profit trends to identify changes in business performance.

---

## Project Structure

Retail-Sales-Intelligence/
│
├── Sample - Superstore.csv
├── Cleaned_Superstore.csv
├── Retail_Sales_Analysis.ipynb
├── Retail_Sales_Dashboard.xlsx
├── README.md
└── images/
    └── dashboard.png

---

## Conclusion

This project demonstrates how Python and Excel can be used together to analyze retail sales performance and profitability.

Python was used for data inspection, numerical analysis, aggregation, and visualization, while Excel was used to create an interactive business dashboard with KPI cards, PivotTables, charts, and slicers.

The analysis provides a structured view of sales, profit, discounts, regional performance, customer segments, and product performance to support better business decision-making.

---

## Author

Your Name:Sreepadmanabhan s.p

Data Analytics Portfolio Project
