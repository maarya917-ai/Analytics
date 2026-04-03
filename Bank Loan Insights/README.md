# Bank Loan Insights

An interactive Power BI dashboard analyzing financial loan data to uncover key banking metrics, loan performance, and portfolio health.

## Overview

This project examines a dataset of bank loans to provide a comprehensive view of loan issuance, repayment trends, risk distribution, and borrower profiles. The dashboard enables data-driven decision-making for banking and financial analysts.

## Project Structure

```
Bank Loan Insights/
├── data/
│   └── financial_loan.csv          # Raw loan dataset
├── powerBI/
│   ├── bank_loan_data_insights.pbix  # Power BI dashboard file
│   └── analytical_BI_report.pdf      # Exported analytical report
└── assets/
    ├── overview_snapshot.png         # Dashboard overview screenshot
    ├── summary_snapshot.png          # Summary view screenshot
    └── details_snapshot.png          # Detailed metrics screenshot
```

## Key Insights

- **Loan Portfolio Overview** — Total loans issued, funded amounts, and repayment rates
- **Loan Status Breakdown** — Distribution across fully paid, current, and charged-off loans
- **Borrower Profiles** — Analysis by employment length, home ownership, and purpose
- **Regional Analysis** — Loan distribution across U.S. states
- **Monthly Trends** — Month-over-month changes in loan applications and disbursements

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Power BI | Dashboard creation and data visualization |
| CSV | Raw data storage |

## Data Source

`financial_loan.csv` — Contains loan-level records including loan amount, interest rate, term, grade, purpose, loan status, and borrower attributes.

## How to Use

1. Open `powerBI/bank_loan_data_insights.pbix` in Power BI Desktop
2. The data is embedded — no additional setup required
3. Use slicers to filter by loan grade, purpose, state, or time period
