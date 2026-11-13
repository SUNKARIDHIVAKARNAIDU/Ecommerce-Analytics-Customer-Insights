# E-Commerce Business Intelligence & Customer Analytics

## Project Overview
This project focuses on analysing e-commerce order data to identify business trends, understand customer purchasing behaviour, and generate actionable business insights.

The project uses a synthetic dataset containing 10,000 e-commerce orders.

## Project Objectives
- Understand and clean raw e-commerce data.
- Perform exploratory data analysis (EDA).
- Analyse sales and product category performance.
- Understand customer purchasing behaviour.
- Identify repeat and one-time customers.
- Create visualisations to communicate business insights.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code

## Dataset
The dataset contains 10,000 records and 19 columns, including:
- Order information
- Customer demographics
- Product categories
- Pricing and discounts
- Payment methods
- Sales channels
- Order status
- Delivery information
- Customer ratings

## Project Structure

```text
Ecommerce_Analytics_ML/
│
├── data/
│   ├── ecommerce_orders_10000.csv
│   └── ecommerce_orders_cleaned.csv
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_cleaning.ipynb
│   └── 03_exploratory_data_analysis.ipynb
│
├── outputs/
│   └── eda_charts/
│
└── README.md
```

## Key Findings
- Analysed 10,000 e-commerce orders.
- Delivered orders accounted for approximately ₹64.08 lakh in net sales.
- Electronics contributed approximately 58.1% of delivered-order net sales.
- Pune recorded the highest city-level net sales.
- The repeat-customer percentage was 81.33% among customers with delivered orders.
- August 2024 recorded the highest monthly delivered-order net sales.

## Business Recommendations
- Monitor high-performing product categories.
- Investigate cancelled and returned orders.
- Develop customer retention strategies.
- Evaluate city-level marketing opportunities.
- Monitor monthly sales trends.

## Project Status
**Data Analytics Stage: Completed**

Future scope:
- Customer segmentation using K-Means.
- Order status prediction.
- Delivery time prediction.
- Interactive business dashboard.

## Note
This project uses synthetic data for educational and portfolio purposes. Findings should not be interpreted as actual business performance.