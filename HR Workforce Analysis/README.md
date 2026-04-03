# HR Workforce Analysis

An interactive Power BI dashboard providing deep insights into human resources metrics, employee trends, and departmental performance.

## Overview

This project analyzes HR data to help organizations understand their workforce composition, attrition patterns, satisfaction levels, and department-wise performance. It supports data-driven HR decision-making.

## Project Structure

```
HR Workforce Analysis/
├── data/
│   └── HR_Analytics.csv             # Employee HR dataset
├── analysis/
│   └── (analytical workbooks)
├── assets/
│   ├── dashboard_snapshot.png        # Main dashboard view
│   ├── RnD_snapshot.png             # R&D department insights
│   ├── sales_snapshot.png           # Sales department insights
│   └── background.png               # Dashboard background
└── docs/
    └── Analytical_Dashboard.pdf      # Exported dashboard report
```

## Key Insights

- **Workforce Overview** — Total headcount, active employees, and attrition rate
- **Attrition Analysis** — Breakdown of employee departures by department, age group, and tenure
- **Department Deep-Dives** — Dedicated views for R&D and Sales departments
- **Satisfaction Metrics** — Job satisfaction, work-life balance, and environment satisfaction scores
- **Demographic Analysis** — Age, gender, marital status, and education level distributions

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Power BI | Dashboard creation and visualization |
| CSV | Raw HR data storage |

## Data Source

`HR_Analytics.csv` — Contains employee-level data including department, job role, education, satisfaction scores, attrition status, and performance ratings.

## How to Use

1. Open `analysis/HR_Insights_&_Trends.pbix` in Power BI Desktop
2. Data is embedded — no additional configuration required
3. Use department and demographic slicers to drill into specific segments
