# Customer Churn Analysis — Banking Domain

A Power BI dashboard analyzing customer churn patterns in a retail banking context, built to help banks identify at-risk customers and understand the drivers behind churn.

## Project Overview

This project explores customer attrition data from a bank to surface patterns across demographics, credit behavior, and product usage. The goal is to provide actionable intelligence to reduce churn and improve customer retention strategy.

## Folder Structure

```
Customer Churn Analysis Report -Banking Domain/
├── Banking Domain - Customer Churb Analysis Report.pbix   # Main Power BI dashboard
├── RBC_BusinessRequirementDocument.docx                   # Business requirement document
└── Datasets/
    ├── Bank_Churn.csv          # Core churn fact table
    ├── CustomerInfo.csv        # Customer demographic details
    ├── ActiveCustomer.xlsx     # Active customer reference
    ├── ExitCustomer.xlsx       # Exited (churned) customer reference
    ├── CreditCard.xlsx         # Credit card ownership lookup
    ├── Gender.xlsx             # Gender dimension table
    └── Geography.xlsx          # Geography dimension table
```

## Key Insights

- **Churn Rate by Geography** — Identifies which countries or regions have the highest customer exit rates
- **Credit Score Segmentation** — Correlates credit score ranges with likelihood of churn
- **Age & Tenure Analysis** — Highlights age groups and tenure bands most prone to leaving
- **Product Holdings** — Examines how the number of bank products a customer holds affects retention
- **Gender Breakdown** — Compares churn rates between male and female customer segments
- **Active vs. Inactive Members** — Explores the relationship between account activity and churn

## Tools Used

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard development and visualization |
| Microsoft Excel | Dimension table management |
| CSV (flat files) | Raw fact data ingestion |
| Microsoft Word | Business requirements documentation |

## Data Sources

| File | Description |
|------|-------------|
| `Bank_Churn.csv` | Core dataset with churn flag, credit score, balance, and product info |
| `CustomerInfo.csv` | Customer age, tenure, and estimated salary |
| `ActiveCustomer.xlsx` | Lookup for active/inactive member classification |
| `ExitCustomer.xlsx` | Lookup for churned vs. retained customers |
| `CreditCard.xlsx` | Credit card ownership flag lookup |
| `Gender.xlsx` | Gender ID to label mapping |
| `Geography.xlsx` | Country ID to name mapping |

## How to Use

1. Open `Banking Domain - Customer Churb Analysis Report.pbix` in Power BI Desktop.
2. If prompted, update the data source paths to point to the local `Datasets/` folder.
3. Refresh the data model to load the latest dataset values.
4. Use the report filters (geography, gender, product count) to drill into specific segments.
5. Reference `RBC_BusinessRequirementDocument.docx` for the original analytical requirements and KPI definitions.
