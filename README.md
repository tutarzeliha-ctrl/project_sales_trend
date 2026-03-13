# project_sales_trend

> "Sales data analysis + visualization + automated PDF report (Python)"

## Overview

Analyzes monthly sales data to identify patterns in campaign performance and stock availability impact on revenue. This project demonstrates data preparation, time-series analysis, automated reporting workflows, and BigQuery SQL analysis.

## Business Question

How do marketing campaigns and inventory levels affect monthly sales performance? Which cities and categories drive the highest spending?

## Methodology

- **Data Source:** Monthly sales transactions (CSV format) + Sepetix e-commerce dataset (BigQuery)
- **Analysis Approach:** Time-series trend detection, campaign impact measurement, stock correlation analysis, city/category segmentation
- **Deliverable:** Automated PDF report with visualizations + BigQuery SQL queries

## Key Findings

- **Campaign Impact:** Marketing campaigns increased sales by 40% compared to non-campaign periods
- **Stock Constraints:** October showed a revenue drop due to stock shortage
- **Seasonal Patterns:** Sales trend peaks in August and November, indicating seasonal demand
- **BigQuery Analysis:** Istanbul's home appliances segment generates an average spend of 4,480 — nearly double the category average
- **Category Insight:** Electronics combines high average spend with high order volume, making it the strongest growth opportunity

## Tools & Technologies

- **Python** - Data processing and analysis
- **Pandas** - Data manipulation and aggregation
- **Matplotlib** - Data visualization
- **ReportLab** - Automated PDF report generation
- **BigQuery** - SQL analysis and segmentation

## Project Structure
```
project_sales_trend/
├── queries/
│   └── sepetix_city_category_analysis.sql
├── data/
│   └── sales_data.csv
├── visuals/
│   └── sales_plot.png
├── report/
│   └── Sales_Trend_Report.pdf
└── README.md
```

## How to Run

1. Install dependencies: `pip install pandas matplotlib reportlab`
2. Run your analysis code
3. PDF report is automatically saved in `report/` directory

## What I Learned

- Time-series analysis techniques for identifying trends
- Correlation analysis between external factors (campaigns, stock) and revenue
- Automated report generation for business stakeholders
- BigQuery CTE + Window Functions for city/category segmentation

## Author

**Zeliha Tutar**
Data Analyst | Decision Intelligence
[LinkedIn](#) | [GitHub](#)

*Focused on translating data into actionable business decisions*

---

**Note:** This project was developed as part of my data analytics learning journey, focusing on real-world business problem-solving.
