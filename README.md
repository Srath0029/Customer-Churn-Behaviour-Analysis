# Customer Churn Analysis

## Overview
This project analyses customer churn using a telecom dataset of over 7,000 customers.  
The goal was to identify key drivers of churn and translate analytical findings into
actionable business insights.

## Business Question
Which customer characteristics are most predictive of churn, and how can these
insights inform retention strategies?

## Dataset
- Telecom customer churn dataset (7,032 customers after cleaning)
- Mixture of demographic, contract, service usage, and billing features

## Approach
- Data cleaning and preprocessing using pandas
- Feature engineering (tenure groups, pricing indicators, service counts)
- Exploratory data analysis to uncover churn patterns
- Logistic regression model to identify key churn predictors

## Key Findings
- Month-to-month customers churned at significantly higher rates than customers on
  one-year or two-year contracts.
- Two-year contracts were the strongest churn-reducing factor.
- High monthly charges substantially increased churn risk, indicating strong price sensitivity.
- Longer tenure customers were significantly less likely to churn.

## Model Performance
- Logistic Regression accuracy: ~77%
- Model chosen for interpretability and business insight, not just prediction

## Tools Used
- Python
- pandas, numpy
- scikit-learn
- matplotlib / seaborn

## Next Steps
- Test additional models (tree-based)
- Add customer lifetime value analysis
- Explore targeted retention strategies for high-risk segments