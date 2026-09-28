# Python Sales Data Analysis

## Project Overview

This project analyzes an online retail sales dataset using Python and Pandas.

The goal is to explore sales performance and identify patterns across products, countries, months, and customers.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

## Dataset

The project uses the **Online Retail Dataset** from the UCI Machine Learning Repository.

The dataset contains retail transactions with information about invoices, products, quantities, prices, dates, customers, and countries.

## Data Cleaning

The analysis included:

* Removing cancelled transactions.
* Removing records with non-positive unit prices.
* Calculating revenue for each transaction.
* Handling missing Customer IDs when performing customer-level analysis.

## Analysis

The project explores:

* Overall sales KPIs
* Top 10 products by revenue
* Top 10 countries by revenue
* Monthly revenue trends
* Top 10 customers by revenue

## Key Results

* Total revenue: approximately **£10.67M**
* Number of unique invoices: **19,960**
* Number of products: **3,922**
* Countries represented: **38**
* Highest-revenue country: **United Kingdom**
* Highest-revenue month: **November 2011**
* Highest-revenue product: **REGENCY CAKESTAND 3 TIER**
* Highest-revenue customer with an available Customer ID: **Customer 14646**

## Project Structure

```text
Python-Sales-Analysis/
│
├── data/
│
├── notebook/
│   └── sales_analysis.ipynb
│
└── README.md
```

## Notebook

The complete analysis and visualizations are available in:

`notebook/sales_analysis.ipynb`
