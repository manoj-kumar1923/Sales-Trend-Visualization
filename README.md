# 📊 Sales Trend Visualization
A professional Excel-based sales analytics project for tracking and visualizing monthly sales performance across product categories.

## 📁 Project Structure

```
sales-trend-visualization/
├── Sales_Trend_Visualization.xlsx   # Main Excel workbook
├── create_excel.py                  # Python script to regenerate the workbook
├── README.md                        # Project documentation
├── .gitignore                       # Git ignore rules
└── sample_data/
    └── sales_data.csv               # Raw sample data (CSV format)
```

## 📋 Workbook Overview

The Excel workbook contains **3 sheets**:

| Sheet | Description |
|-------|-------------|
| `Sales Data` | Raw monthly sales data for 5 product categories with MoM growth and YTD cumulative formulas |
| `Dashboard` | Visual KPI cards + Line chart (monthly trend) + Bar chart (category comparison) |
| `Summary & Insights` | Narrative key insights and strategic recommendations |

## 🗂️ Data Details

- **Time Period**: FY 2024 (Jan – Dec)
- **Product Categories**: Electronics, Apparel, Home & Garden, Sports, Beauty
- **Metrics Tracked**:
  - Monthly sales per category
  - Monthly total revenue
  - Month-over-Month (MoM) growth %
  - Year-to-Date (YTD) cumulative revenue
  - Annual totals per category

## 📊 Charts & Visuals

- **Line Chart** — Monthly total sales trend (smooth, styled)
- **Bar Chart** — Annual sales by product category
- **KPI Cards** — Total Revenue, Best Month, Top Category, Annual Growth %
