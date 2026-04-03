# Stock Trading Report — Equity Market Dashboard

A Power BI dashboard analyzing stock market performance across multiple equities, with color-coded visual themes for both light and dark presentation modes.

## Project Overview

This project provides a visual analysis of stock trading data across multiple tickers, tracking price movements, volume trends, and market behavior. The report is delivered in two visual themes — white and black — for flexibility across presentation contexts. A ticker reference file supports filtering and identification across the equity universe covered.

## Folder Structure

```
Trading Report/
├── Stock Treding Report.pbix                   # Main Power BI dashboard
├── ColorCodes.xlsx                              # Color palette reference used in the report
├── tickername.xlsx                              # Ticker symbol reference list
├── Stock Treding Report_White.pdf               # Exported report — white theme
├── Stock Treding Report_White_page-0001.jpg     # White theme — page 1 preview
├── Stock Treding Report_White_page-0002.jpg     # White theme — page 2 preview
├── Stock Treding Report_black.pdf               # Exported report — black theme
├── Stock Treding Report_black_page-0001.jpg     # Black theme — page 1 preview
├── Stock Treding Report_black_page-0001.png     # Black theme — page 1 (PNG format)
└── Stock Treding Report_black_page-0002.jpg     # Black theme — page 2 preview
```

## Key Insights

- **Price Trend Analysis** — Historical price movement for individual stocks and the broader portfolio
- **Volume Tracking** — Trade volume patterns identifying high-activity periods and anomalies
- **Ticker Comparison** — Side-by-side performance comparison across multiple equity symbols
- **Dual-Theme Presentation** — White and black themed exports for professional and investor-facing use cases
- **Color-Coded Visuals** — Custom color scheme defined in `ColorCodes.xlsx` for consistent branding across charts

## Tools Used

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard development and visualization |
| Microsoft Excel | Ticker reference and color palette data |

## Data Sources

| File | Description |
|------|-------------|
| `tickername.xlsx` | Reference list of stock ticker symbols included in the analysis |
| `ColorCodes.xlsx` | Custom color codes used to style visuals consistently |

*Note: The underlying stock price and volume data is embedded within the `.pbix` file.*

## How to Use

1. Open `Stock Treding Report.pbix` in Power BI Desktop.
2. The core data is embedded — no external source reconnection is required.
3. Ensure `tickername.xlsx` and `ColorCodes.xlsx` are in the same folder if data refresh is needed.
4. Use ticker slicers to isolate individual equities or compare a subset of stocks.
5. For static viewing, open `Stock Treding Report_White.pdf` or `Stock Treding Report_black.pdf` depending on your preferred visual theme.
