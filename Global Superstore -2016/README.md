# Global Superstore 2016 — Sales & Profitability Analysis

A Power BI dashboard built on the 2016 Global Superstore dataset, providing a worldwide view of sales, profit, and shipping performance across markets, categories, and customer segments.

## Project Overview

This project leverages the well-known Global Superstore 2016 dataset to deliver a comprehensive analysis of international retail operations. It surfaces revenue and profitability trends across countries, product categories, and customer segments, with a particular focus on global market dynamics that differentiate it from US-only superstore analyses.

## Folder Structure

```
Global Superstore -2016/
├── Global Superstore Report_Jaydeep_Patel.pbix   # Main Power BI dashboard
└── global_superstore_2016.xlsx                    # Source dataset (Global Superstore 2016)
```

## Key Insights

- **Global Market Performance** — Sales and profit comparison across regions: APAC, EU, LATAM, US, Africa, and more
- **Category Profitability** — Margin analysis across Technology, Furniture, and Office Supplies
- **Top & Bottom Markets** — Countries and cities with the highest and lowest profit margins
- **Customer Segmentation** — Revenue split across Consumer, Corporate, and Home Office segments
- **Shipping Mode Impact** — Effect of shipping class (Same Day, First Class, etc.) on cost and profitability
- **Discount Analysis** — Relationship between discount levels and profit erosion

## Tools Used

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard development and visualization |
| Microsoft Excel | Source data (Global Superstore 2016 dataset) |

## Data Sources

| File | Description |
|------|-------------|
| `global_superstore_2016.xlsx` | Full Global Superstore 2016 dataset including Orders, Returns, and People sheets — covers sales across 147 countries |

## How to Use

1. Open `Global Superstore Report_Jaydeep_Patel.pbix` in Power BI Desktop.
2. If prompted, update the data source path to point to `global_superstore_2016.xlsx` in the same folder.
3. Refresh the data model to reload the dataset.
4. Use the region and country slicers to focus on specific markets.
5. Filter by year, category, or segment to drill into specific dimensions of performance.
