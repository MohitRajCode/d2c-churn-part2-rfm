# D2C Customer Churn - Part 2: RFM Segmentation

## Project Overview

This project performs customer segmentation using the RFM (Recency, Frequency, Monetary) framework to identify valuable customer groups and design retention strategies.

## Dataset

The analysis uses:

- Customer profiles
- Order history
- Churn labels

## Methodology

1. Remove post-snapshot data to prevent leakage.
2. Calculate Recency, Frequency, and Monetary values.
3. Generate RFM scores using quantiles.
4. Create customer segments.
5. Analyze churn across segments.
6. Propose retention strategies.

## Customer Segments

- Champions
- Loyal Customers
- Potential Loyalists
- At Risk

## Key Findings

- Champions exhibit lower churn rates.
- At Risk customers have higher churn probability.
- RFM segmentation helps prioritize retention efforts.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Repository Structure

```text
d2c-churn-part2-rfm/
│
├── rfm_segmentation.ipynb
├── retention_strategy.md
├── README.md
└── requirements.txt
```
