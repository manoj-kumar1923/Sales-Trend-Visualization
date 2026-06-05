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

## 🚀 Getting Started

### Prerequisites
- Microsoft Excel 2016+ **or** LibreOffice Calc 7+
- Python 3.8+ (only if regenerating the workbook)

### Open the Workbook
1. Clone this repository:
   ```bash
   git clone https://github.com/manoj-kumar1923/Sales-Trend-Visualization/blob/main/Sales_Trend_Visualization%5B1%5D.xlsx
   ```
2. Open `Sales_Trend_Visualization.xlsx` in Excel or LibreOffice Calc.
3. Navigate to the **Dashboard** sheet for the visual summary.

### Regenerate the Workbook (Optional)
```bash
pip install openpyxl
python create_excel.py
```

## 🛠️ Customization

To use your own data:
1. Open the `Sales Data` sheet.
2. Replace the values in columns B–F (rows 5–16) with your actual sales figures.
3. All formulas (totals, growth %, YTD) will auto-recalculate.
4. Charts on the Dashboard will update automatically.

## 🎨 Design Conventions

| Color | Meaning |
|-------|---------|
| 🔵 Dark Blue `#1F3864` | Headers, primary labels |
| 🔵 Mid Blue `#2E75B6` | Sub-headers, KPI cards |
| 🟡 Gold `#FFC000` | Annual totals row |
| ⚪ White / Light Blue | Alternating data rows |

## 📄 License

MIT License — feel free to use, modify, and distribute.

## 🙌 Contributing

Pull requests are welcome! For major changes, please open an issue first.
