# Sales Data Analysis Dashboard

## Overview

This project analyzes sales data using SQL and Python to extract actionable business insights such as revenue trends, regional performance, and product-level analysis.

## Tech Stack

* Python
* SQL (SQLite)
* Pandas
* Matplotlib
* Jupyter Notebook

## Key Features

* Revenue analysis by region
* Monthly sales trend visualization
* Top-performing product identification
* SQL queries integrated with Python
* Data cleaning and transformation pipeline

## Key Insights

* Identified top-performing regions contributing the highest share of total revenue
* Observed clear monthly sales trends indicating seasonal variations
* Found that top 2 products contribute disproportionately to total sales (Pareto pattern)
* Revenue distribution highlights potential areas for business optimization

## Visualizations

### Revenue by Region

![Revenue by Region](revenue_by_region.png)

### Product Revenue Ranking

![Product Ranking](product_ranking.png)

## Project Structure

* `sales_analysis.ipynb` → Main analysis notebook
* `sales.csv` → Dataset
* `sales.db` → SQLite database
* `revenue_by_region.png` → Region-wise revenue chart
* `product_ranking.png` → Product ranking chart

## How to Run

1. Clone the repository
2. Open `sales_analysis.ipynb` in Jupyter Notebook
3. Run all cells sequentially

## Future Improvements

* Build an interactive dashboard using Streamlit
* Add advanced SQL queries (window functions, CTEs)
* Implement predictive modeling for sales forecasting
