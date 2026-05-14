# E-Commerce Sales & Profit Analysis

A data analysis project built on the Sample Superstore dataset to uncover sales trends, profitability patterns, and customer segment insights using Python and Plotly.

---

## Overview

This project analyzes retail e-commerce data across multiple dimensions — time, product categories, sub-categories, and customer segments — to help understand what drives sales and profit in a superstore environment.

---

## Analysis Covered

1. **Monthly Sales Analysis** — Identifies which month had the highest and lowest sales
2. **Category-wise Sales** — Compares sales performance across product categories
3. **Sub-category Sales** — Breaks down sales at a granular sub-category level
4. **Monthly Profit Analysis** — Tracks profit trends over months and finds the peak profit month
5. **Category & Sub-category Profit** — Analyzes profitability at both category and sub-category levels
6. **Customer Segment Analysis** — Compares sales and profit across Consumer, Corporate, and Home Office segments
7. **Sales to Profit Ratio** — Measures how efficiently each segment converts sales into profit

---

## Dataset

- **Source:** Sample Superstore Dataset (CSV)
- **Key Columns:** Order Date, Category, Sub-Category, Segment, Sales, Profit, Quantity, Discount

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.12 | Core language |
| Pandas | Data manipulation and aggregation |
| Plotly Express | Interactive charts |
| Plotly Graph Objects | Custom visualizations |
| Jupyter Notebook | Development environment |

---

## Key Findings

- The **Consumer** segment generates the highest sales but also has the highest Sales-to-Profit ratio (~8.66), meaning profit margins are comparatively thinner
- **Corporate** and **Home Office** segments show better profit efficiency
- Sales and profit vary significantly across months, categories, and sub-categories

---

## How to Run

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install pandas plotly jupyter
   ```
3. Place the `Sample - Superstore.csv` file in the project directory and update the file path in the notebook
4. Open the notebook:
   ```bash
   jupyter notebook E-commerce_analysis2.ipynb
   ```
5. Run all cells to generate the analysis and visualizations

---

[LinkedIn](https://linkedin.com/in/sonukumar08/)

