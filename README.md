# Project 6 – Retail Customer & Revenue Analysis

Analysis of 900 retail orders from 149 customers using Python (pandas), SQLite, and Tableau Public.

**Interactive Dashboards:** [View on Tableau Public](paste-your-link-here)

## Key Findings
- Total revenue was $111,656.93, with an average order value of $145.39. Revenue is an estimate, since 132 orders (about 15%) have unknown revenue.
- 15 high-value customers have not ordered in over 90 days. They represent $19,252 (17.2% of revenue) and are at risk of churning.
- Order frequency drives customer revenue (r = 0.67), while customer tenure has almost no effect (r = −0.05). Encouraging repeat orders matters more than customer longevity.

## Data Quality
- 132 orders have unknown revenue: 118 missing unit price, 16 missing quantity (2 missing both).
- 48 orders have an unknown region and 79 an unknown category.
- 8 customer IDs in the orders file have no matching customer record.
- All gaps are documented in the analysis rather than filled with estimates.

## Tools
Python, pandas, SQLite, scipy, Matplotlib/Seaborn, Tableau Public

## Data Note
The dataset is synthetic and was generated for portfolio practice. It contains no real customer information.
