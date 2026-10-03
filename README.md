# Alura Store — Sales Performance Analysis

Which of 4 retail stores should be sold? Analysis of revenue, product categories, ratings, best/worst sellers, and shipping cost per store.

## Data

- 4 CSVs (one per store) from the Alura LatAm data-science challenge: product, category, price, customer rating, shipping cost, and geolocation (lat/lon) per sale.

## Analysis

Per store: total revenue, sales by product category, average customer rating, most/least sold products, average shipping cost. Compared with bar charts, pie charts, line charts, and geographic scatter plots.

## Results

| Store | Total revenue | Avg. rating | Avg. shipping cost |
|---|---|---|---|
| Store 1 | 1,150,880,400 | 3.98 | 26,019 |
| Store 2 | 1,116,343,500 | 4.04 | 25,216 |
| Store 3 | 1,098,019,600 | 4.05 | 24,806 |
| Store 4 | 1,038,375,700 | 4.00 | 23,459 |

Store 4 has the lowest revenue by a clear margin (~112M below Store 1). Ratings and shipping costs are similar across all four stores, so revenue is the deciding factor.

**Recommendation: sell Store 4** and reinvest the capital in a new business.

## Reproduce

```bash
pip install pandas matplotlib
```

Open `alura_store_sales_analysis.ipynb` in Jupyter or Google Colab and run all cells.

## Context

Built for the Alura Store data-science challenge (Oracle Next Education).
