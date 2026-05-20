# Sales-analytics
# E-commerce Sales & User Behavior Analysis

> Exploratory and statistical analysis of an online store — sales performance,
> user behavior, and traffic sources using SQL, Python and Tableau Public.
> Contributed as **Data Analyst** (SQL, BigQuery, Python, Tableau Public).

[![SQL](https://img.shields.io/badge/SQL-BigQuery-4285F4?logo=google-cloud&logoColor=white)](https://cloud.google.com/bigquery)
[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)](YOUR_NOTEBOOK_LINK)
[![Tableau Public](https://img.shields.io/badge/Tableau-Public-E97627?logo=tableau&logoColor=white)](YOUR_TABLEAU_LINK)

---

## Project Description

End-to-end analysis of an online store based on the internal course database
(data-analytics-mate, Google BigQuery). The project covers sales performance by
product, geography and device, user behavior analysis (registered vs unregistered),
traffic source analysis, sales dynamics with seasonality detection, and statistical
hypothesis testing.

---

## Tools

- **SQL** (Google BigQuery) — data extraction with complex JOINs, CTEs
- **Python** (Google Colab) — data cleaning, EDA, pivot tables, statistical analysis
- **Pandas** — data transformation and aggregation
- **Matplotlib / Seaborn** — data visualization
- **SciPy / Statsmodels** — statistical testing (Pearson correlation, Mann-Whitney U, Kruskal-Wallis, ANOVA, z-test)
- **Tableau Public** — interactive dashboard

---

## Analysis Notebook

The full analysis is available in Google Colab:
[Open notebook →](YOUR_NOTEBOOK_LINK)

### Notebook structure

1. Database Connection — connecting to Google BigQuery (data-analytics-mate)
2. Data Inspection — data types, shape, missing values
3. Overall Sales & User Behavior Analysis
   - 3.1 Sales by product category and country (global and USA)
   - 3.2 Top 10 most profitable products
   - 3.3 Sales by device type and browser
   - 3.4 Sales by traffic source
   - 3.5 Registered vs unregistered users behavior
4. Sales Dynamics Analysis
   - 4.1 Overall sales dynamics and seasonality
   - 4.2 Sales by continent (Americas, Asia, Europe)
   - 4.3 Sales by traffic channel
   - 4.4 Sales by device type
5. Pivot Tables
   - 5.1 Sessions by traffic channel and device type
   - 5.2 Sales by top-10 categories in top-5 countries
   - 5.3 Monthly revenue from top-4 products
6. Statistical Relationship Analysis
   - 6.1 Sessions vs registered users (Pearson correlation)
   - 6.2 Sessions vs total sales (Pearson correlation)
   - 6.3 Sales correlation across top-3 continents
   - 6.4 Sales correlation across traffic channels
   - 6.5 Sales correlation across top-5 product categories
7. Statistical Analysis of Differences Between Groups
   - 7.1 Registered vs unregistered users (Mann-Whitney U test)
   - 7.2 Sessions by traffic channel (Kruskal-Wallis test)
   - 7.3 Organic search share: Europe vs Americas (z-test)
   - 7.4 Revenue from top product by continent (ANOVA)
8. Conclusions and Recommendations

---

## Key Findings

- **Americas drives 55%+ of total sales**, with the US alone accounting for 43.6%; top 4 categories (Sofas & armchairs, Chairs, Beds, Bookcases & shelving units) generate 72% of revenue
- **Top 4 products** (GRÖNLID, LIDHULT, VIMLE, KIVIK) account for 22.35% of total revenue and 61.51% of the most profitable category
- **Unregistered users generate 11× more revenue** than registered users with nearly identical average order values (956 vs 929) — registration provides insufficient value or has UX barriers
- **Clear sales seasonality**: peak in early December (~700K) and early January (~610K); Organic Search shows the strongest seasonal fluctuations
- **Desktop + Chrome dominates** with 49.3% of sales; mobile Safari and Chrome together account for 35%+ — mobile optimization is critical
- **Statistically significant positive correlation** between sales across all continents (r ≈ 0.77–0.79, p < 0.05) and traffic channels (r up to 0.87), suggesting synchronized demand driven by seasonal or marketing factors

---

## Links

- [Tableau Dashboard](YOUR_TABLEAU_LINK) — interactive visualization
- [Analysis Notebook](YOUR_NOTEBOOK_LINK) — Google Colab
