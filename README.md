# Superstore Sales Analysis - Task 2

**Repository contents:**  
- `Visualization.pdf` — PDF with the graphs (Sales by Category, Profit by Sub-Category, Sales Trend Over Time). 
- `data/` — place your `superstore.csv`.  
- `scripts/make_and_merge_charts.py` — Python script to generate the missing charts (Sales by Region, Top 10 Customers) and merge them into an updated PDF.  
- `requirements.txt` — Python dependencies.  
- `.gitignore` — recommended ignores.  
- `LICENSE` — MIT license.

## Objective
Add the two missing charts required by the internship task:
1. **Sales by Region** (bar chart)  
2. **Top 10 Customers** (horizontal bar chart)

The included script will:
- read `data/superstore.csv`
- create `new_charts.pdf` containing the two charts
- merge `docs/Task2_Data_Analyst_Report.pdf` + `new_charts.pdf` into `docs/Task2_Data_Analyst_Report_updated.pdf`

## Quick start (recommended)
1. Put your `superstore.csv` into `data/` (CSV must contain columns: `Region`, `Sales`, `Customer Name`).  
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   # Linux / macOS
   source venv/bin/activate
   # Windows
   venv\Scripts\activate
   pip install -r requirements.txt
