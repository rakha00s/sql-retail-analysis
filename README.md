# Retail Sales Analysis

**Status:** 🚧 In progress

## Business question
Which regions and product categories drive revenue, and where is growth slowing?

## Data
- **Source:** [Dataset name and link, e.g. Olist E-commerce on Kaggle]
- **Size:** [rows / tables]
- **Cleaning notes:** [nulls, duplicates, date formats you fixed]

## Tools
SQL ([PostgreSQL / SQLite / BigQuery]) · Tableau

## Approach
1. Explored the schema and built an ERD (`docs/erd.png`)
2. Cleaned and joined tables (`sql/01_cleaning.sql`)
3. Analyzed revenue by region, category, and month using CTEs and window functions (`sql/02_analysis.sql`)
4. Built a cohort/retention view (`sql/03_cohorts.sql`)
5. Visualized results in Tableau

## Key insights
- [Insight with a number, e.g. "Top 3 regions generate 62% of revenue"]
- [Insight 2]
- [Insight 3]

## Recommendation
[One or two sentences on what the business should do.]

## Links
- 📊 Live dashboard: [Tableau Public link]
- 💻 Queries: [`/sql`](./sql)

## Repo structure
```
data/        sample data or download instructions
sql/         numbered query files
dashboard/   screenshots
docs/        ERD and notes
```
