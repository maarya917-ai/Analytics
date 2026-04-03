# Sales Performance Analysis

A Power BI dashboard analyzing sales performance across regions, time periods, and product categories using the Superstore dataset.

## Overview

This project examines sales data from a retail superstore to identify performance trends, regional differences, and year-over-year growth patterns. The dashboard supports strategic sales planning and territory management decisions.

## Project Structure

```
Sales Performance Analysis/
├── data/
│   └── sample_-_superstore.xls - Orders.csv   # Superstore orders data
├── analysis/
│   └── (analytical workbooks)
├── assets/
│   ├── preview.jpg              # Dashboard overview
│   ├── reg_east_2016.jpg        # East region 2016 snapshot
│   ├── reg_west_2017.jpg        # West region 2017 snapshot
│   └── sales_2014.jpg           # 2014 sales snapshot
├── Sales_Analysis.pbix          # Power BI dashboard
└── Overview.pdf                 # Exported PDF report
```

## Key Insights

- **Regional Performance** — Sales comparison across East, West, Central, and South regions
- **Year-over-Year Trends** — Annual sales growth from 2014 through 2017
- **Category Analysis** — Revenue breakdown by product category and sub-category
- **Profitability** — Profit margins and discount impact by segment
- **Top Performers** — Best-selling products and highest-value customers

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Power BI | Interactive dashboard and visualization |
| CSV / XLS | Raw sales order data |

## Data Source

`sample_-_superstore.xls - Orders.csv` — Contains order-level records including order date, region, category, sales, profit, and customer segment.

## How to Use

1. Open `Sales_Analysis.pbix` in Power BI Desktop
2. Data is embedded — no additional setup required
3. Use region and year slicers to filter the view by territory or time period
