# Restaurant Sales Dashboard Project

## Project Overview
This project presents an interactive Excel-based sales dashboard built from restaurant order data. The goal was to analyze overall performance, top-selling items, and customer behavior across multiple ordering channels and time periods.

---

## Objective
To provide clear business insights by visualizing key restaurant metrics such as:
- Total orders
- Total revenue
- Cost per customer
- Sales by location
- Top 10 food items
- Sales trends by month and order category

---

## Key Metrics & Visuals

### Filters
- **System Date**: Interactive slicer to filter data by year (2020–2024)
- **Day & Month**: Filters for analyzing sales trends by weekdays and months

### KPIs
- **Total Orders**: 129,116  
- **Total Revenue**: $591,371.78  
- **Cost per Customer**: $29

### Visuals
- **Restaurant Sales (Bar Chart)** – Location-wise revenue  
- **Category Orders (Pie Chart)** – Share by order type: EatStreet, DoorDash, Take Outs  
- **Top 10 Items (Line Chart)** – Best-performing food items  
- **Monthly Sales (Column Chart)** – Seasonal revenue trends  

---

## Steps Followed

### 1. Data Cleaning
- Removed duplicates and null values  
- Standardized column names and formats (e.g., dates, categories)  
- Merged sheets to unify raw data for processing

### 2. Power Query
- Imported and transformed data for analysis  
- Applied filters, grouped values, and generated date hierarchies  
- Created calculated columns such as “Cost per Customer” and “Order Category”

### 3. Pivot Tables
- Built summaries for key dimensions: Item, Category, Location, Month  
- Connected pivot tables to slicers for real-time filtering  
- Used calculated fields to support custom metrics

### 4. DAX Formulas (via Power Pivot)
- Implemented measures like:
  - `Total Orders = COUNTROWS(Table)`
  - `Total Revenue = SUM(Table[Amount])`
  - `Cost per Customer = [Total Revenue] / [Total Orders]`

### 5. Dashboard Creation
- Designed visual layout using charts, slicers, and formatting  
- Added KPIs with visual icons for enhanced readability  
- Applied color themes for clarity and focus

### 6. Macros (if applicable)
- Automated data refresh and slicer reset functionality  
- Improved usability for dashboard users

---

## Tools Used
- Microsoft Excel  
- Power Query  
- Pivot Tables & Pivot Charts  
- DAX (Power Pivot)  
- Macros (VBA for automation)

---

## Summary
This dashboard provides a holistic view of restaurant performance and customer preferences. It helps stakeholders make informed decisions on menu planning, promotional timing, and regional sales strategies.

---

## Note
This is a personal project built for analytical practice and visualization improvement using Excel. The dataset used is fictional or simulated for demonstration purposes.

