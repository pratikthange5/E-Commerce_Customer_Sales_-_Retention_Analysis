# E-Commerce Customer Sales & Retention Analysis

## Overview
A recruiter-friendly Python EDA project that analyzes e-commerce sales, customers, products, discounts, profitability, and customer inactivity.

## Business Problem
The company wants to understand what drives sales, which customer segments generate the most revenue, how discounts relate to profitability, and which customers are becoming inactive.

## Tools
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## Project Structure
```text
ecommerce_customer_eda/
├── data/
│   └── ecommerce_sales.csv
├── notebooks/
│   └── ecommerce_eda.ipynb
├── src/
│   ├── data_generation.py
│   ├── data_cleaning.py
│   └── analysis.py
├── visualizations/
├── README.md
└── requirements.txt
```

## Analysis Covered
1. Data understanding
2. Data cleaning
3. Feature engineering
4. Univariate analysis
5. Bivariate analysis
6. Time-series EDA
7. Customer value analysis
8. Customer inactivity analysis
9. Discount and profitability analysis
10. Correlation analysis
11. Simple independent two-sample t-test
12. Business insights and recommendations

## Customer Activity Rules
- Active: 0–30 days since last order
- Recently Inactive: 31–90 days
- Inactive: 90+ days

These are business rules for analysis, not machine-learning predictions.

## Important Interpretation Rule
The project uses association/correlation language for discount and profitability. It does not claim that discounts cause lower profit margins.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/ecommerce_eda.ipynb
```

The dataset is synthetic and reproducible. The notebook contains the complete analysis workflow.
