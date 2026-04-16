# Retail-Sales-PowerBI-Dashboard
An end-to-end Power BI dashboard designed to analyze retail sales performance, uncover high-return products, and enable secure, user-based data access using Dynamic Row Level Security (RLS).

The project focuses on transforming raw retail data into actionable insights through interactive visuals, KPI tracking, and enhanced tooltip-driven user experience.

## Project Overview
This project analyzes retail sales data to uncover insights on sales performance, returns, and regional trends.
The dashboard provides a clear view of
- Sales growth over time
- Top-performing regions
- Category contribution
- Product-level performance
- Return behavior

## Project Workflow
- Imported retail dataset into Power BI
- Performed data cleaning and transformation
- Built star schema data model
- Created DAX measures for KPIs
- Designed interactive dashboard visuals
- Implemented tooltip for better UX
- Applied Dynamic Row Level Security (RLS)
- 
## Dataset
This project uses the AdventureWorks dataset, a Microsoft sample dataset that simulates a real-world retail business.
It includes:
- Sales transactions across multiple years
- Product hierarchy (Category, Subcategory, Product)
- Customer and regional data
- Returns data for analyzing product performance
  
The dataset was used to build a star schema data model and perform sales and return analysis.

## Business Problem
- Retail businesses often struggle to:
- Identify high-return products
- Track regional performance
- Understand sales vs returns impact

This dashboard helps stakeholders make data-driven decisions by highlighting key patterns.
## Key Insights
- Accessories dominate sales (~70% contribution), indicating strong demand concentration in a single category
- Return percentage remains low (~2%), indicating efficient sales
- Certain top-selling products also have higher returns
- Regions like Australia and Southwest perform strongly

## Features Implemented
- KPI Cards (Total Orders, Quantity, Returns, Net Quantity, Return %)
- Dynamic filtering using slicers (Year, Category, Region)
- Region-wise performance analysis
- Category contribution analysis
- Top-performing products visualization
- Custom tooltip for detailed hover insights
- Dynamic Row Level Security (RLS)

## Interactive Visuals
- Sales trend over time
- Region-wise performance
- Category contribution
- Top 5 products
- Tooltip (Advanced UX)

## Custom tooltip showing:
- Total Orders
- Total Returns
- Return % on hover over regions
- Row Level Security (RLS)

## Dynamic RLS implemented using:
Dynamic RLS implemented using USERPRINCIPALNAME()

A mapping table is used to restrict users to their respective regions, ensuring:
- Secure data access
- Personalized data views
- Scalable user-based filtering

Also handled scenario where specific users can access multiple regions.

## Dashboard Overview
*Displays overall sales performance with KPIs, trends, and filters.*
<p align="center">
  <img src="Overview.png" width="800"/>
</p>

### Deep Dive Analysis
<p align="center">
  <img src="Deep-dive.png" width="800"/>
</p>

## Tooltip Experience (Advanced UX)
<p align="center">
  <img src="ToolTip.png" width="800"/>
</p>

## Data Model
<p align="center">
  <img src="Data-Modelling.png" width="800"/>
</p>

## Tools Used
- Power BI
- DAX
- Data Modeling
- GitHub (for project documentation)

## Learnings
- Implemented dynamic Row Level Security (RLS) using USERPRINCIPALNAME() and a user-region mapping table
- Designed user-friendly tooltip for better UX
- Built a structured data model for performance optimization
- Translated business problems into actionable insights

## Business Impact
- Helps identify products with high return rates
- Enables region-wise performance comparison
- Supports data-driven decision-making
- Ensures secure and personalized data access using RLS

## Conclusion
This project demonstrates the ability to build end-to-end Power BI solutions, combining data modeling, DAX, visualization, and security to deliver business-ready insights.
