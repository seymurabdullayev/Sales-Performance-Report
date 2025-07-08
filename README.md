# Sales-Performance-Report
The Sales Performance Report project is an interactive Power BI dashboard designed to analyze and visualize sales data. It includes key performance indicators such as total sales, total profit, total cost, and the percentage variation in sales and profit. Additionally, the dashboard allows users to view sales and profit data from previous years. 

## About the Project
This is a personal portfolio project titled Sales Performance Report, developed in Power BI to analyze and visualize sales data using a structured data model and meaningful KPIs. The goal is to provide insightful analysis of sales performance through dynamic and interactive visualizations.

Key steps and features of the project:
- Multiple datasets were imported from Excel, including 1 fact table and 6 dimension tables.
- Necessary data cleaning tasks were performed such as data type corrections, column renaming, and establishing proper table relationships.
- A Calendar (Date) table was created and linked to the model for accurate time-based analysis.
- Key DAX measures were created, including:
  1. Total Sales, Total Profit, Total Cost, Order Count
  2. Previous Year Sales and Profit
  3. Profit Variation %, Sales Variation %
         
- The dashboard includes the following insights:
  1. Total Sales, Total Profit, Order Count, Total Quantity
  2. Monthly and Weekly Sales Trends
  3. Top 5 Product Sales
  4. Brand-wise Total Sales
  5. Sales by Promotion
  6. Sales and Profit by Sales Channel
     
This project demonstrates my skills in data modeling, DAX calculations, and interactive visualization using Power BI, and it reflects my ability to turn raw data into actionable business insights.

## The used tools and technologies
- Power BI (data modeling, DAX, visualizations)
- Microsoft Excel (data source)
- DAX (measures for KPIs and comparative analysis)
- Power Query (data transformation and cleaning)

## Data Preparation and Cleaning

- Imported an Excel file named "Sales" containing all relevant tables into Power BI.
- Separated tables into fact and dimension tables for proper data modeling.
- Corrected data types for each column to ensure accurate calculations.
- Renamed columns clearly and consistently for better readability.
- Created a separate "Date" table using the calendar function, which includes columns for year, month, day of the week, and month number.
- Established relationships between the fact table and the "Date" table.

## Measures Creation

- All necessary measures for analysis were created collectively within a single measure group rather than scattered individually.
- This approach improves accessibility and organization of measures within the dashboard.
- Created measures include total sales, total profit, total cost, order count, previous year sales and profit, as well as percentage variations in sales and profit.

## Dashboard Previews
![General_Analyze](https://github.com/seymurabdullayev/Sales-Performance-Report/blob/1c33a0acda09b5b15a1201c812f394f2b6dfbd5f/General_Analyze%20.png)

![Regional_Analyze](https://github.com/seymurabdullayev/Sales-Performance-Report/blob/7902235ae7e5e894fdbc6aaa30ed592f9b659722/Regional_Analyze%20.png)

## How to Use

1. Download the `https://github.com/seymurabdullayev/Sales-Performance-Report/blob/ba5fbc22bfa6a08625ddb8954c35e3c346533466/Sales_Performance_Report.pbix` file from this repository.
2. Open it using Power BI Desktop.
3. Review the visualizations and interact with filters and slicers.



