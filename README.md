# Lab 3 - Data Engineering & EDA with Python, SQL, and Pandas

## Project Overview
This project simulates a corporate environment where we manage employee and department data. The objective is to perform **Data Engineering** (ETL) and **Exploratory Data Analysis (EDA)** to derive actionable business insights regarding operational health and talent ROI.

## Project Structure

```text
Lab3 - Data Engineering & EDA with Python, SQL, and Pandas/
├── .gitignore              # Specifies intentionally untracked files to ignore
├── requirements.txt        # List of Python packages required to run the analysis
├── README.md               # Project overview and setup instructions
└── Lab3_DataAnalysis.ipynb # Main Jupyter Notebook containing code, EDA, and visualizations
```

## Core Model & Architecture
* **Data Generation**: Uses `Faker` to simulate a realistic workforce of 50 employees and various departments.
* **Database**: Managed via **Neon SQL (PostgreSQL)**.
* **Integration**: Combines SQL-based data retrieval with Pandas for advanced feature engineering (e.g., years of service, salary-to-revenue ratios).

## Advanced Visualization Challenge (Part 7)
The analysis is broken down into four key purposes:
1. **Financial Performance**: Comparing Revenue vs. Budget per department.
2. **Talent ROI**: Analyzing Revenue per Head vs. Staffing Cost Ratio using dual-axis charts.
3. **Pay Equity**: Examining the correlation between experience and compensation (identifying Salary Inversion).
4. **Regional Analysis**: Evaluating cost-efficiency and headcount across Toronto, Waterloo, Vancouver, and Remote teams.

## Key Insights (Main Observation)
* **Efficiency**: Demonstrated a high-scalability model with staffing costs at only 3%–5.5% of revenue.
* **Strategic Growth**: Identified Waterloo and Vancouver as high-efficiency hubs for future expansion.
* **Risk Alert**: Noted a "Salary Inversion" trend requiring a compensatory audit to protect core technical assets in a lean 50-person team.

## How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Execute the Jupyter Notebook cells in sequence.