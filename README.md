🛒 Online Sales Data Analysis Dashboard
📊 Overview

This project focuses on analyzing and visualizing online sales performance across different regions, product categories, and time periods. The analysis was performed using Python (Pandas, Matplotlib, Seaborn) for data preprocessing and Power BI for interactive dashboard creation.

🧩 Project Components
1. Data Cleaning & Analysis (Python)

File: untitled17.py

Performed using:

Pandas for data manipulation

NumPy for numerical operations

Matplotlib & Seaborn for data visualization

Key steps:

Loaded dataset: Online Sales Data.csv

Checked for missing values and dataset structure

Generated descriptive statistics

Verified revenue consistency using:

df['Check_Revenue'] = df['Units Sold'] * df['Unit Price']


Prepared the cleaned dataset for visualization in Power BI

2. Power BI Dashboard

File: Sales_Dashboard.pbix

The dashboard provides interactive visuals for exploring:

Total Sales: 80.57K

Sales by Month: Trend showing January peak at ~14.5K

Sales by Region:

North America – 37K

Asia – 22K

Europe – 21K

Sales by Product Category: Electronics lead the sales share

Filters: Quarter, Region, and Product Category slicers for dynamic exploration

Visuals included:

KPI card (Total Sales)

Donut chart (Sales by Product Category)

Line chart (Sales by Month)

Bar chart (Sales by Region)

Slicers (Quarter, Region, Product Category)

🧠 Insights

Electronics dominate overall sales.

North America is the highest revenue-generating region.

Sales show a declining trend after Q1.

May–July experienced the lowest sales volume.

🛠️ Tools & Technologies

Python: Data preprocessing

Power BI: Data visualization

Libraries Used: Pandas, NumPy, Matplotlib, Seaborn

Dataset: Online Sales Data (CSV format)

📁 Project Structure
├── untitled17.py                # Python data cleaning and validation script
├── Online Sales Data.csv        # Source dataset (not included)
├── Sales_Dashboard.pbix         # Power BI report file
├── Screenshot.png               # Dashboard preview
└── README.md                    # Project documentation

📷 Dashboard Preview

🚀 How to Use

Run the Python script to clean and verify the dataset:

python untitled17.py


Load the cleaned dataset into Power BI.

Interact with the dashboard — filter by quarter, region, or category to analyze patterns.
