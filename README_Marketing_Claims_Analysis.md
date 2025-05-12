
# Marketing Campaign & Claims Analysis

This project analyzes an auto insurance dataset to support two key business objectives:

- Predict Total Claim Amounts using linear regression
- Forecast customer response to marketing campaigns using classification models

## Key Outcomes

- Linear Regression model achieved **R² = 0.76**, MAE = 94.8
- Decision Tree Classifier achieved **F1-score = 0.89**
- EDA revealed strong predictors including Monthly Premium Auto and Customer Lifetime Value
- Addressed class imbalance using stratified sampling and evaluated models with precision, recall, and F1-score

## Tools Used

- Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
- SQL (for structured querying and validation)
- Tableau (for visualization and interactive dashboards)

## Business Impact

- Improves claim forecasting for pricing and underwriting
- Enhances marketing efficiency by identifying likely responders
- Promotes data-driven, cost-effective outreach strategies

## Conclusions
The dataset analyzed contained customer demographic information, vehicle and insurance policy details, and marketing response history. My goal was to support two key business objectives: predicting a customer’s total claim amount using regression, and forecasting marketing campaign response using classification.

The regression model, trained to estimate total claims, achieved a mean absolute error of 94.8 and an R² of 0.76, indicating a strong fit. This allows the company’s underwriting and finance teams to better assess financial risk, price premiums more accurately, and maintain profitability while improving customer satisfaction.

For classification, I aimed to identify which customers are likely to respond positively to marketing efforts. The Decision Tree model performed best, with scores above 0.8 across precision, recall, and F1-score. This will enable the marketing team to efficiently focus on high-potential customers, personalize offers, and avoid wasting resources on low-probability targets.

A key limitation was a significant class imbalance in responses, which was addressed by using stratified sampling and balanced class weights, though some bias risk remains. Ethical considerations include the use of sensitive variables like employment and education in predictions, which may affect fairness. Transparency and regular model audits are recommended for responsible implementation.

## Dataset

Contains 99,134 customer records and 51 features including demographic info, policy data, and marketing response.

**Author**: [Olayemi Olugosi]  
**Date**: [04/28/2025]
