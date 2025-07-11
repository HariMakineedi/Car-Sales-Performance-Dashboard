# Car-Sales-Performance
##  Project Objective

The goal of this project is to visualize and analyze year-to-date car sales data using Power BI. This dashboard helps track key performance metrics such as total sales, average price, units sold, and regional performance. It also enables users to filter data by body style, color, transmission type, and dealer, supporting strategic business decisions through interactive and dynamic reporting.
##  Dataset

You can download the dataset used in this project here:  
[📄 Car Sales.xlsx](https://github.com/HariMakineedi/Car-Sales-Performance-Dashboard/blob/main/Car%20Sales.xlsx)

##  KPI Questions for the Dashboard

 **How many cars were sold YTD?**  
 **What is the total YTD sales revenue?**  
 **What is the average price per car?**  
 **Which region sold the most cars?**  
 **Which dealer has the highest sales?**  
 **Which body style is most popular?**  
 **What is the top-selling car color?**  
 **Which engine type generates the most revenue?**  
 **What are the weekly sales trends?**  
 **How do MTD sales compare to YTD?**  
 **Which transmission type sells better: Automatic or Manual?**  
 **What is each region's % contribution to total sales?**

 ##  Project Process

### 1.  Data Collection
- Gathered car sales data in Excel format (`Car Sales.xlsx`) containing detailed attributes like region, dealer name, color, engine type, body style, and sales figures (YTD & MTD).

### 2.  Data Cleaning & Preparation
- Used **Power Query** in Power BI to:
  - Remove duplicates and null values
  - Standardize data formats (e.g., date, currency)
  - Rename columns and split/merge fields for analysis readiness

### 3.  Data Modeling
- Loaded the cleaned data into Power BI
- Created relationships between fields such as:
  - Region → Dealer → Sales Metrics
  - Body Style / Engine / Transmission → Sales & Pricing
- Defined calculated columns and measures using **DAX**

### 4.  Dashboard Design
- Built interactive visuals including:
  - KPIs: Total Sales, Cars Sold, Avg. Price
  - Charts: Bar, Pie, Line, Column
  - Slicers: Region, Body Style, Transmission, Color
- Applied a clean, user-friendly layout with consistent formatting

### 5.  Insight Generation
- Analyzed top-performing regions and dealers
- Identified trends in customer preferences (e.g., popular colors and styles)
- Compared MTD vs YTD performance
- Highlighted strategic metrics for business decision-making

