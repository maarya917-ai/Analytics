# U.K. Road Accident Analysis

A Power BI dashboard analyzing road accident data across the United Kingdom to identify safety patterns, high-risk conditions, and vehicle-type distributions.

## Overview

This project examines U.K. road accident records to surface insights about casualty trends, accident severity, road and weather conditions, and vehicle types involved. The findings can support road safety policy decisions and infrastructure improvements.

## Project Structure

```
U.K. Road Accident Analysis/
├── Road_Accident_Analysis.pbix     # Power BI dashboard (includes embedded data)
├── Datasets.txt                    # Link to source dataset on Google Drive
└── assets/
    ├── Background Image.png        # Dashboard background
    ├── Car.png                     # Vehicle icon - car
    ├── Bus.png                     # Vehicle icon - bus
    ├── Van.png                     # Vehicle icon - van
    ├── Bike 3.png                  # Vehicle icon - bike
    ├── tractro 2.png               # Vehicle icon - tractor
    └── Other.png                   # Vehicle icon - other vehicles
```

## Key Insights

- **Casualty Overview** — Total casualties broken down by severity (fatal, serious, slight)
- **Vehicle Type Analysis** — Accident distribution across cars, buses, vans, bikes, and other vehicles
- **Road Conditions** — Casualty counts by road surface, road type, and speed limit
- **Lighting & Weather** — Impact of daylight vs. darkness and weather conditions on accidents
- **Year-over-Year Comparison** — Trend analysis comparing current vs. prior year casualties
- **Geographic Hotspots** — Location-based accident density mapping

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Power BI | Dashboard creation and visualization |
| External dataset | U.K. road accident records (see Datasets.txt) |

## Data Source

The accident dataset is sourced externally (link provided in `Datasets.txt`). It contains road accident records including date, severity, vehicle type, road conditions, weather, and location coordinates.

## How to Use

1. Open `Road_Accident_Analysis.pbix` in Power BI Desktop
2. Data is embedded within the PBIX file
3. Use the year toggle to switch between current and previous year views
4. Filter by vehicle type, road type, or severity for focused analysis
