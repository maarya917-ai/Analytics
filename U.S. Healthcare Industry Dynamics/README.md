# U.S. Healthcare Industry Dynamics

A comprehensive multi-dimensional Power BI analytics solution examining U.S. hospital operations, patient outcomes, physician performance, and payer dynamics.

## Overview

This project delivers an enterprise-grade healthcare analytics platform built on a star-schema data model. It covers the full spectrum of healthcare operations — from hospital financials and provider metrics to patient diagnosis patterns and payer reimbursements — enabling strategic decision-making across clinical and administrative domains.

## Project Structure

```
U.S. Healthcare Industry Dynamics/
├── analytics/
│   └── US-healthcare-dynamics.pbix          # Primary analytics dashboard
├── data/
│   ├── FactTable.csv                        # Central fact table
│   ├── DimHospital.csv                      # Hospital dimension
│   ├── DimPatient.csv                       # Patient dimension
│   ├── DimPhysician.csv                     # Physician dimension
│   ├── DimPayer.csv                         # Insurance payer dimension
│   ├── DimSpeciality.csv                    # Medical speciality dimension
│   ├── DimDate.csv                          # Date dimension
│   ├── DimCptCode.csv                       # CPT procedure codes
│   ├── DimDiagnosisCode.csv                 # Diagnosis codes
│   ├── DimTransaction.csv                   # Transaction records
│   ├── AdjustmentFactor(%).csv              # Reimbursement adjustment factors
│   ├── BadDepthTable.csv                    # Data quality reference
│   ├── DataDictionary.csv                   # Field definitions
│   ├── data-dictionary.csv                  # Extended data dictionary
│   └── Healthcare_Dataset.xlsb              # Consolidated Excel dataset
├── notes/
│   ├── Building_Reports.pdf                 # Report development guide
│   ├── Business_Intelligence.pdf            # BI methodology documentation
│   ├── Case.pdf                             # Case study overview
│   ├── DAX.pdf                              # DAX measures reference
│   ├── Data_Model.pdf                       # Star schema documentation
│   ├── Data_Transformation.pdf             # ETL and transformation steps
│   ├── Ground_Rules.pdf                     # Project ground rules
│   └── Healthcare_Case_Study.pdf           # Full case study document
├── assets/
│   ├── er-diagram.png                       # Entity-relationship diagram
│   ├── executive_summary.jpg                # Executive summary dashboard
│   ├── hospital_insights.jpg                # Hospital metrics view
│   ├── healthcare_provider_metrics.jpg      # Provider performance view
│   ├── patient_outcome_analysis.jpg         # Patient outcomes view
│   ├── monthly_expenses_trends.jpg          # Expense trends view
│   ├── project_overview.jpg                 # Project overview page
│   └── purpose_section.jpg                  # Purpose and scope page
├── dashboards.pbix                          # Additional dashboard file
├── report.pdf                               # Exported analytics report
└── schema.png                               # Data model schema diagram
```

## Key Insights

- **Executive Summary** — High-level KPIs: total revenue, encounters, procedures, and costs
- **Hospital Insights** — Performance comparison across hospital facilities
- **Provider Metrics** — Physician productivity, procedure counts, and revenue by specialty
- **Patient Outcomes** — Diagnosis distribution, readmission patterns, and length-of-stay analysis
- **Payer Dynamics** — Reimbursement rates, adjustments, and payer mix analysis
- **Monthly Expense Trends** — Cost patterns and budget variance over time

## Data Model

The project uses a **star schema** with one central fact table surrounded by dimension tables:

| Table | Description |
|-------|-------------|
| FactTable | Core transactions linking all dimensions |
| DimHospital | Hospital attributes and location |
| DimPatient | Patient demographics |
| DimPhysician | Provider details and specialty |
| DimPayer | Insurance payer information |
| DimSpeciality | Medical specialties |
| DimCptCode | CPT procedure codes |
| DimDiagnosisCode | ICD diagnosis codes |
| DimDate | Date hierarchy for time intelligence |

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Power BI | Multi-page dashboard and visualization |
| DAX | Calculated measures and KPIs |
| CSV / XLSB | Dimensional and fact data storage |

## How to Use

1. Open `analytics/US-healthcare-dynamics.pbix` in Power BI Desktop
2. Data is embedded — no additional setup required
3. Navigate through report pages: Executive Summary → Hospital Insights → Provider Metrics → Patient Outcomes → Payer Analysis
4. Refer to `notes/DAX.pdf` for measure documentation and `notes/Data_Model.pdf` for schema details
