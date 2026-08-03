# Umai Frozen Yogurt Customer Demand Dashboard

## Project Overview

This project analyzes customer traffic across 20 Umai Frozen Yogurt franchise locations in California using more than 21,000 daily sales records collected over three years.

The Excel dashboard was created to help a sales executive compare average daily customer traffic and examine whether location, date, rainfall, and temperature were associated with changes in customer demand.

## Business Questions

- How did average daily customer traffic change over the three-year period?
- Did customer traffic vary across franchise locations?
- Was customer traffic lower during periods of intense rainfall?
- Was temperature meaningfully associated with customer volume?
- How could these patterns support operational planning?

## Tools Used

- Microsoft Excel
- Power Pivot
- Excel Data Model
- PivotTables and PivotCharts
- SQL Server
- Regression Analysis
- Slicers and Filters

## Data Preparation and Modeling

- Imported store and daily sales data from SQL Server into the Excel Data Model
- Created a relationship between the Sales and Stores tables
- Built a calendar hierarchy using year, month, and day-of-week fields
- Summarized more than 21,000 records across 20 franchise locations
- Connected multiple PivotTables and charts to a shared city slicer

## Dashboard Components

The Sales Report includes:

- A line chart comparing average daily customers over time
- A rainfall analysis comparing customer traffic under different weather conditions
- A scatter chart examining temperature and average customer volume
- A city slicer allowing users to filter all report visuals by franchise location

## Regression Analysis

Regression analysis was used to evaluate the relationship between temperature and customer traffic.

The model produced an R-squared value of 0.73, indicating that temperature explained approximately 73% of the variation in customer count within the dataset. The relationship was statistically significant.

In business terms, temperature appeared to be a meaningful predictor of customer demand and could be considered when planning staffing, inventory, and promotional activities.

## Business Value

The dashboard brings location, calendar, and weather-related customer patterns into one interactive Excel report.

It allows managers to compare franchise performance, explore customer traffic under different conditions, and identify factors that could support demand planning and operational decisions.

## Project File

The complete Excel dashboard and analysis are available in:

`Umai_Customer_Demand_Dashboard.xlsx`

## Dashboard Preview

Dashboard screenshots will be added when the workbook is available for preview.
