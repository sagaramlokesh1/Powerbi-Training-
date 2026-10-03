# 📊 Power BI Training

## 📌 Overview

This repository contains my hands-on Power BI training exercises,
practice files, dashboards, and data analysis projects.

The training focuses on transforming raw data into meaningful business
insights using Power Query, data modeling, DAX, interactive
visualizations, and dashboard development.

## 🎯 Learning Objectives

- Understand the Power BI workflow
- Import and connect to different data sources
- Clean and transform data using Power Query
- Build relationships between tables
- Create effective data models
- Develop calculated columns and measures using DAX
- Create interactive reports and dashboards
- Analyze business KPIs and trends
- Apply filters, slicers, and drill-down functionality
- Build decision-ready business reports

## 🛠️ Tools & Technologies

| Technology | Usage |
|---|---|
| Power BI Desktop | Data Analysis & Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | Measures & Calculated Columns |
| Excel | Data Source & Data Preparation |
| SQL | Data Extraction & Analysis |

## 📚 Topics Covered

### 1. Power BI Fundamentals
- Power BI Desktop Interface
- Data Import
- Data Types
- Report View
- Data View
- Model View

### 2. Power Query
- Removing duplicates
- Handling missing values
- Changing data types
- Splitting and merging columns
- Conditional columns
- Append Queries
- Merge Queries
- Group By
- Data transformation

### 3. Data Modeling
- Fact and Dimension Tables
- Primary and Foreign Keys
- Table Relationships
- One-to-Many Relationships
- Star Schema
- Date Tables

### 4. DAX

DAX concepts practiced include:

- SUM()
- SUMX()
- COUNT()
- COUNTROWS()
- DISTINCTCOUNT()
- AVERAGE()
- CALCULATE()
- FILTER()
- IF()
- SWITCH()
- DIVIDE()
- RELATED()
- DATE()
- YEAR()
- MONTH()
- QUARTER()
- UNION()
- INTERSECT()
- EXCEPT()

### 5. Date Table

Example:

    DimDate =
    ADDCOLUMNS(
        CALENDAR(
            MIN('Order Data'[Order_Date]),
            MAX('Order Data'[Order_Date])
        ),
        "Month", FORMAT([Date], "MMMM"),
        "MonthNo", MONTH([Date]),
        "Quarter", "Q" & QUARTER([Date]),
        "QuarterNo", QUARTER([Date]),
        "Year", YEAR([Date])
    )

### 6. Data Visualization

Worked with:

- Bar Charts
- Column Charts
- Line Charts
- Pie/Donut Charts
- Tables
- Matrix
- Cards
- KPI Cards
- Slicers
- Maps
- Drill-down
- Tooltips

## 📊 Dashboard Development

The training includes building interactive dashboards for analyzing:

- Sales Performance
- Revenue
- Profit
- Orders
- Customers
- Products
- Regional Performance
- Monthly and Yearly Trends
- Business KPIs

## 📂 Repository Structure

    PowerBI-Training/
    │
    ├── Datasets/
    │   ├── Sales_Data.xlsx
    │   └── Order_Data.xlsx
    │
    ├── Power_Query/
    │   └── Data_Cleaning.pbix
    │
    ├── DAX/
    │   └── DAX_Practice.pbix
    │
    ├── Dashboards/
    │   ├── Sales_Dashboard.pbix
    │   └── Order_Analysis.pbix
    │
    ├── Screenshots/
    │   └── Dashboard.png
    │
    └── README.md

## 💡 Skills Developed

- Power BI
- Power Query
- DAX
- Data Cleaning
- Data Transformation
- Data Modeling
- Data Analysis
- KPI Development
- Dashboard Development
- Data Visualization
- Business Intelligence
- Analytical Problem Solving

## 👤 Author

**Sagaram Lokesh**

Data Analyst | Business Analyst | MIS Analyst |  
Power BI Developer | Dashboard Developer | Python | SQL | Tableau

LinkedIn: linkedin.com/in/sagaramlokesh  
GitHub: github.com/SagaramLokesh
