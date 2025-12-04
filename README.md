content = """
# 📊 Sales Trend Analysis Project

this project analyzes monthly sales data to identify patterns, campaign effects, and stock-related issues.
It includes data preparation, visualization and an automatically generated PDF report.

## Objective
to explore how campaign periods and stock status affect monthly sales performance.

## Tools Used
-Python
-pandas
-matplotlib
-reportlab

## Key Insights
-Campaign months increased sales by -40%.
-October showed a drop due to stock shortage.
-Overall sales trend peaks in August and November


## 📂 Project Structure
project_sales_trend/  
 ├── data/  
 │    └── sales_data.csv  
 ├── visuals/  
 │    └── sales_plot.png  
 ├── report/  
 │    └── Sales_Trend_Report.pdf  
 ├── scripts/ (optional)  
 └── README.md  


## How to Run
1.Install dependencies:
2. Run your analysis code.
3. PDF report is automatically saved in `report/`.

## 📝 Author
Zeliha – Junior Data Analyst
"""

with open("README.md", "w", encoding="utf-8") as f:
 f.write(content)

print("📄 README.md oluşturuldu!")
