# ecommerce-sales-analytics

Sales analytics project — SQL + Python + Tableau dashboard analyzing 35K+ orders and $6.97M revenue

## Overview
This portfolio project demonstrates end-to-end sales analytics for an e-commerce store, using SQL, Python, and Tableau.

## Goals
- Extract data from a database using SQL
- Perform exploratory and statistical analysis in Python
- Build an interactive dashboard in Tableau

## Tools Used
- **SQL** — data extraction
- **Python** (Pandas, Matplotlib/Seaborn) — exploratory & statistical analysis
- **Tableau** — dashboard visualization

## Dashboard
Interactive Tableau dashboard analyzing e-commerce sales data:
- **35,655 orders** and **$6.97M in revenue** analyzed
- Sales trends over time (Nov 2020 – Jan 2021)
- Breakdown by product category and top-selling products
- Geographic analysis by country (orders & revenue)
- Device-based analysis (desktop, mobile, tablet)

🔗 [View live dashboard on Tableau Public](https://public.tableau.com/app/profile/yulia.gutman/viz/Sales_17691055259090/Sales)

## Notebook
[Link to Jupyter Notebook](https://colab.research.google.com/drive/1piFn4KaBBeK1jRmBNsS1lwBY42ZoPhyi?usp=sharing)

## Key Findings
- **Sofas & armchairs** is the top revenue-generating category, significantly ahead of Chairs and Beds
- **United States** dominates revenue generation (~$14M) — more than 5x the next highest country (India)
- **Desktop** remains the primary ordering channel (58.7% of orders), followed by mobile (39.1%) and tablet (2.2%)
- A t-test confirmed a statistically significant difference in revenue between desktop and mobile orders (p-value = 0.0065 < 0.05)
