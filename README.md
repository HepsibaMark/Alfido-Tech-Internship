# Customer Behavior Analysis – Aflido Tech Internship

**Task Overview**

This project was completed as part of the Data Analyst Internship at Aflido Tech.
The goal was to analyze customer transaction and behavioral data to identify customer
segments, purchase patterns, and churn risks.

**Dataset**

[E-Commerce Customer Behavior Data](https://www.kaggle.com/datasets/bhanupratapbiswas/customer-behavior-analysis) — 250,000 transaction records, 49,673 unique customers.

**Tools Used**

Python (Pandas, Matplotlib, Seaborn), Google Colab, RFM (Recency, Frequency, Monetary) segmentation

**Methodology**

1. Cleaned and prepared transaction-level data (handled nulls, fixed date formats, removed duplicate columns)
2. Aggregated data to customer level and computed RFM scores
3. Segmented customers into 6 groups: Champions, Loyal Customers, Potential Loyalist, At Risk, Needs Attention, Lost
4. Profiled each segment (avg. spend, frequency, recency, churn rate, returns)
5. Visualized purchase patterns and retention trends
6. Derived 5 actionable business recommendations

**Key Findings**

- Champions (28% of customers) drive the highest average spend (₹21,385) and order frequency
- Churn rate is flat at 20% across all segments — indicating churn isn't explained by purchase behavior alone
- Lost customers haven't purchased in 717+ days on average
- Monthly active customers and revenue remained stable over the analysis period

**Files**

- `Customer_Behavior_Analysis.ipynb` — Full analysis notebook with code & visualizations
- `Customer_Behavior_Analysis_Report.pdf` — Summary report with findings and recommendations

**Author**

Hepsiba Selvi M — B.Tech AI & Data Science, MIT Chromepet
