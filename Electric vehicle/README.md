# Electric Vehicle Sales Analysis — India

A Power BI dashboard examining electric vehicle (EV) adoption trends across Indian states and manufacturers, with a focus on penetration rates and compound annual growth rate (CAGR).

## Project Overview

This project analyzes monthly EV sales data across Indian states and vehicle makers to track the pace of electrification. It breaks down adoption by 2-wheelers and 4-wheelers, identifies leading states and manufacturers, and benchmarks growth using penetration rate and CAGR metrics.

## Folder Structure

```
Electric vehicle/
├── Electric vehicle.pbix                          # Main Power BI dashboard
├── Electric vehicle.pdf                           # Exported PDF report
├── meta_data.txt                                  # Column descriptions and metric definitions
├── primary_and_secondary_questions.pdf            # Analytical questions guiding the report
└── datasets/
    ├── electric_vehicle_sales_by_state.csv        # Monthly EV sales per state and category
    ├── electric_vehicle_sales_by_makers.csv       # Monthly EV sales per manufacturer
    └── dim_date.csv                               # Date dimension with fiscal year and quarter
```

## Key Insights

- **State-Level Penetration** — Identifies states with the highest share of EVs relative to total vehicle sales
- **Maker Market Share** — Ranks manufacturers by EV units sold across 2-wheeler and 4-wheeler segments
- **Fiscal Year Trends** — Tracks year-over-year growth using India's April–March fiscal calendar
- **CAGR Analysis** — Measures compound annual growth rate for top states and makers over the data period
- **Category Split** — Compares 2-wheeler vs. 4-wheeler EV adoption rates nationally
- **Quarterly Patterns** — Surfaces seasonal demand fluctuations within each fiscal year

## Tools Used

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard development and visualization |
| CSV (flat files) | Raw sales and date dimension data |

## Data Sources

| File | Description |
|------|-------------|
| `electric_vehicle_sales_by_state.csv` | Date, state, vehicle category, EVs sold, and total vehicles sold |
| `electric_vehicle_sales_by_makers.csv` | Date, vehicle category, maker name, and EVs sold |
| `dim_date.csv` | Date, fiscal year, and fiscal quarter mapping |

**Key Metrics Defined:**
- **Penetration Rate** = (Electric Vehicles Sold / Total Vehicles Sold) × 100
- **CAGR** = (Ending Value / Beginning Value)^(1/n) − 1
- **Fiscal Year** runs April 1 – March 31 (India standard)

## How to Use

1. Open `Electric vehicle.pbix` in Power BI Desktop.
2. Update data source paths to the local `datasets/` folder if prompted.
3. Refresh the data model to load all three CSV files.
4. Use state and maker slicers to filter views, or switch between 2-wheeler and 4-wheeler segments.
5. Refer to `meta_data.txt` for full column definitions and `primary_and_secondary_questions.pdf` for the analytical scope.
