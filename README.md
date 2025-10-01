# Vendor Performance Analysis

# [Vendor Performance Analysis Project.pdf](https://github.com/user-attachments/files/22644949/Vendor.Performance.Analysis.Project.pdf)


A comprehensive data analytics project that processes multi-million record datasets to derive actionable insights into vendor performance, procurement strategies, and sales optimization.

## 📊 Project Overview

This end-to-end analytics solution processes raw procurement and sales data to deliver strategic business intelligence through:
- **Data Engineering Pipeline** handling large-scale datasets
- **Advanced Statistical Analysis** of vendor performance
- **Interactive Dashboards** for business decision-making
- **BLOB Data Decoding** for data integrity challenges

## 🛠️ Technical Stack

### Data Engineering & Database
- **Python 3.x** - Core programming language
- **SQLite** - Database management system
- **pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing

### Data Analysis & Statistics
- **SciPy** - Statistical testing (T-tests, confidence intervals)
- **Statistical Methods**:
  - Hypothesis testing
  - Confidence interval analysis
  - Correlation analysis
  - Pareto analysis (80/20 rule)

### Data Visualization
- **Matplotlib** - Static visualizations and charts
- **Seaborn** - Statistical data visualization
- **Power BI** - Interactive dashboards and business reporting

### Data Processing & ETL
- **Custom ETL Pipeline** with timeout handling
- **BLOB Data Decoding** using `struct` module
- **Large-scale data processing** (12M+ records handled)

## 📁 Project Structure
vendor-performance-analysis/
│
├── data/ # Raw data files
│ ├── purchases.csv # 2.3M+ records
│ ├── sales.csv # 12.8M+ records
│ ├── vendor_invoice.csv # Vendor freight data
│ └── inventory_data/ # Inventory records
│
├── database/ # Database files
│ ├── purchases.db # Primary SQLite database
│ └── large_purchases.db # Large sample database
│
├── notebooks/ # Jupyter notebooks
│ ├── exploratory_data_analysis.ipynb
│ ├── vendor_performance_analysis.ipynb
│ └── blob_data_decoding.ipynb
│
├── scripts/ # Python modules
│ ├── database_analyzer.py # Database management class
│ ├── data_ingestion.py # ETL pipeline
│ └── visualization.py # Chart generation
│
├── dashboards/ # Power BI reports
│ └── vendor_performance_dashboard.pbix
│
└── outputs/ # Generated reports & charts
├── performance_metrics/
└── vendor_insights/

