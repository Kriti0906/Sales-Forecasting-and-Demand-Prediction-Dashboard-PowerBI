# Sales Forecasting & Demand Prediction Dashboard (Power BI)

An interactive Power BI dashboard built on the Superstore dataset to analyze historical sales patterns, forecast future demand, and identify peak selling periods to support inventory and business planning decisions.

## Overview

The dashboard answers key business questions:
- Which product sub-categories drive the most revenue?
- How has monthly sales performance trended across years (2022–2024)?
- What does the forecasted sales trend look like for the upcoming months?
- Which months represent peak sales periods that need extra inventory/staffing focus?

**Total Sales Analyzed:** 2.30M

## Tools & Techniques
- **Power BI** – data modeling, DAX measures, and interactive visuals
- **Excel** – data cleaning and preprocessing
- Time-series based **forecasting** for future sales trend projection
- Sub-category level breakdown for granular product performance analysis

## Key Features
- **Sales by Product/Category** – bar chart ranking sub-categories (Phones, Chairs, Storage, etc.) by total sales
- **Monthly Sales Trend** – multi-year (2022/2023/2024) line comparison to spot seasonality
- **Forecasted Sales Trend** – projected monthly sales for the next 12 months
- **Peak Sales Periods** – identifies months with highest demand for planning purposes

## 📁 Repository Contents
| File | Description |
|------|-------------|
| `Sales Forecasting & Demand Prediction Dashboard.pbix` | Power BI source file |
| `Sales Forecasting & Demand Prediction Dashboard.pdf` | Static export of the dashboard |
| `Superstore_dataset.csv` | Raw dataset |
| `Superstore_Project_Dataset_cleaned (1).xlsx` | Cleaned dataset used for analysis |

## Dashboard Preview
![Dashboard Screenshot](screenshots/dashboard.png)


## Key Insights
- Total sales analyzed: **2.30M**, with clear seasonality — sales are uneven across months rather than steady
- Top 3 revenue-driving sub-categories: **Phones, Chairs, and Storage**
- **October and December** are the peak sales months, showing significant, visible growth over other months
- Forecast indicates sales are expected to **hold steady, with a slight potential increase**, in the coming period

## Recommendations
- Adjust storage and supply chain policy ahead of peak months (Oct, Dec) to meet forecasted demand increases
- Prioritize inventory and supply for top-performing sub-categories (Phones, Chairs, Storage)
- Consider reducing supply for low-impact sub-categories that don't meaningfully affect overall sales
- Use the forecast to guide future purchasing and expenditure planning
- Monitor monthly sales regularly to catch deviations early

## How to Use
1. Download the `.pbix` file and open it in Power BI Desktop
2. Or view the static `.pdf` export for a quick look at all dashboard pages
