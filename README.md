# Power BI Retail Analytics Project

## Retail Sales Dashboard & Business Intelligence Solution

---

# Project Overview

This project was built in Power BI to transform raw retail data into meaningful business insights. The workflow included data cleaning, data modeling, DAX calculations, dashboard creation, and data quality validation.

The goal was to help businesses track sales performance, profitability, customer behavior, and product growth through interactive dashboards.

---

# Phase 1: Power Query Transformations

### Completed Tasks

* Imported all 6 CSV files into Power BI
* Created a **Price Segment** column:

  * Premium → UnitCost > 500
  * Budget → UnitCost ≤ 500
* Merged Store Region data into Fact_Sales
* Applied Unpivoting for better table structure
* Created a custom function to clean and format text
* Removed unnecessary columns for better performance

---

# Phase 2: Star Schema Data Modeling

### Data Model Structure

Built a **Star Schema** model using:

* Fact_Sales (Main Table)
* Dim_Product
* Dim_Customer
* Dim_Store
* Dim_Date

### Relationships

All tables were connected using:

* One-to-Many (1:*)
* Single Direction Filtering

To improved report speed and accuracy.

---

# Phase 3: DAX Measures

### Key Measures Created

* Total Sales
* Total Cost
* Profit Margin %
* Sales YTD
* Sales LY
* Sales Growth %
* Running Total
* Top Product

These measures helped analyze business performance and sales trends.

---

# Phase 4: Data Quality Framework

### Quality Checks Applied

* Checked missing SalesAmount values
* Validated Quantity > 0
* Verified sales calculations
* Checked key relationships
* Ensured unique SalesID values
* Identified orphan records
* Validated Discount % range

To improved data reliability and reporting accuracy.

---

# Phase 5: Dashboard Design

## Executive Dashboard

Included:

* KPI Cards
* Sales Trend Line Chart
* Sales Map by City
* Year & Category Filters

## Product & Customer Analysis

Included:

* Top 10 Products
* Profit vs Quantity Scatter Plot
* Customer Segment Matrix
* Navigation & Reset Buttons

---

# Business Insights

The dashboard helped solve important business problems by:

* Identifying top-selling products
* Tracking sales growth trends
* Understanding customer segments
* Measuring profitability accurately
* Improving data quality
* Supporting better business decisions

---

# Conclusion

This project demonstrates a complete Power BI Business Intelligence workflow from raw data to interactive reporting.

Using Power Query, Star Schema modeling, DAX, and dashboard visualization, the project successfully converted retail data into actionable business insights that help businesses improve performance and make smarter decisions.
