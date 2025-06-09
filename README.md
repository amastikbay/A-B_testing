# A/B Testing Project

This repository contains a complete A/B Testing case study performed in Python. 

The objective was to statistically evaluate whether a company should invest in new webpage design.

## 🔧 Used libraries
- Python (Pandas, NumPy)
- `statsmodels` for statistical testing
- `scipy.stats` for Z-tests and confidence intervals

## 📂 Dataset
- The dataset `ab_data.csv` includes user-level data for a web experiment.
- Each row represents a user and their assigned group - control or treatment and whether they converted.

## 🧪 Methodology
1. **Data Cleaning**: Checked and removed nulls and inconsistencies.
2. **Exploratory Analysis**: Grouped and visualized conversion ratios.
3. **Statistical Testing**: Used Z-test for two proportions to determine statistical significance of differences in conversion.

## 📈 Business Impact
This analysis is a real-world decision happening everyday in a product analytics whether to launch a new web design. Applying statistical methods the goal is to make data-driven decisions that affects user engagement and revenue.
