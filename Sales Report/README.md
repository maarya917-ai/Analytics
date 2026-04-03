# Sales Report — Multi-Year Performance Dashboard

A Power BI dashboard tracking company sales performance across 2014–2017, broken down by sales representative, product category, sub-category, and geography.

## Project Overview

This project analyzes internal company sales data spanning four years to identify trends in revenue, geographic performance, product mix, and individual sales rep contribution. Unlike public retail datasets, this report uses a structured star-schema data model with dedicated dimension tables for clean, scalable analysis.

## Folder Structure

```
Sales Report/
├── Sales Report_Jaydeep_Patel.pbix    # Main Power BI dashboard
└── Datasets/
    ├── Sales/
    │   ├── Sales 2014.csv             # Transaction data for 2014
    │   ├── sales 2015.csv             # Transaction data for 2015
    │   ├── sales 2016.csv             # Transaction data for 2016
    │   └── sales 2017.csv             # Transaction data for 2017
    └── Dimensions/
        ├── Categories.xlsx            # Product category lookup
        ├── SubCategories.xlsx         # Product sub-category lookup
        ├── Product.csv                # Product master data
        ├── Geography.xlsx             # Region and territory mapping
        └── SalesRep.xlsx              # Sales representative details
```

## Key Insights

- **Year-over-Year Growth** — Revenue trends from 2014 through 2017 with annual comparisons
- **Sales Rep Performance** — Individual rep rankings by revenue and target attainment
- **Category & Sub-Category Mix** — Revenue and margin breakdown across product lines
- **Geographic Distribution** — Territory-level sales performance and regional variance
- **Seasonal Patterns** — Monthly and quarterly demand fluctuations within each year

## Tools Used

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard development, data modeling, and visualization |
| CSV (flat files) | Annual sales transaction data |
| Microsoft Excel | Dimension tables (categories, geography, sales reps) |

## Data Sources

| File | Description |
|------|-------------|
| `Sales 2014–2017.csv` | Annual transaction records with product, rep, geography, and revenue |
| `Categories.xlsx` | Product category ID to name mapping |
| `SubCategories.xlsx` | Sub-category lookup linked to parent categories |
| `Product.csv` | Full product master with IDs, names, and sub-category links |
| `Geography.xlsx` | Territory and region mapping for geographic drill-downs |
| `SalesRep.xlsx` | Sales rep IDs, names, and region assignments |

## How to Use

1. Open `Sales Report_Jaydeep_Patel.pbix` in Power BI Desktop.
2. If prompted, update data source paths to point to the `Datasets/Sales/` and `Datasets/Dimensions/` folders.
3. Refresh the data model — all four annual sales files will load automatically.
4. Use the year slicer to compare performance across 2014, 2015, 2016, and 2017.
5. Filter by sales rep, category, or geography to drill into specific slices of the business.
