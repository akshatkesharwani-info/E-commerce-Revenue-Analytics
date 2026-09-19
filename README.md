# E-commerce Revenue Analytics

A SQL-based revenue analytics pipeline built on over a million real e-commerce transactions.

## Problem
Leadership needs a single source of truth on revenue, customer retention, and product performance
-- without waiting on ad-hoc spreadsheet requests every time a question comes up.

## What It Does
- Cleans a transactional dataset (removes cancellations, missing customer IDs, bad rows)
- Loads the cleaned data into SQL and answers core business questions with real queries
- Computes repeat-customer rate and average order value
- Produces a monthly revenue trend and top-10-products-by-revenue view, ready for a BI dashboard

## Real Results (real dataset -- 1,067,371 transaction rows)
- **Repeat customer rate: 69.8%** -- the large majority of customers come back more than once
- **Average order value: $479.95**
- Full monthly revenue trend and top-product breakdown exported and ready for Power BI

## Tech Stack
Python, Pandas, SQLite/SQL, Matplotlib, Power BI

## How to Run
Open in Google Colab, run all cells. Dataset (Online Retail II, over a million rows) auto-
downloads via `kagglehub`, with a synthetic fallback if it ever fails.
