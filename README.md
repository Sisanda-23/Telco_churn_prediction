# Predicting Customer Churn & Revenue Risk (Telecom)

## Business Problem
Customer churn is a major source of revenue loss in the telecom industry.
The goal of this project is to identify customers at high risk of churning so
the business can take proactive retention actions.

## Dataset
- Telco Customer Churn dataset (Kaggle)
- ~7,000 customers
- Demographic, service usage, and billing information

## Approach
1. Data cleaning and preprocessing
2. Feature encoding and selection
3. Model training and evaluation:
   - Logistic Regression
   - Decision Tree
4. Model comparison using ROC-AUC, precision, and recall
5. Business interpretation of results

## Models & Results

| Model | ROC-AUC | Churn Recall |
|-----|--------|-------------|
| Logistic Regression | 0.84 | 0.57 |
| Decision Tree | 0.82 | 0.52 |

Logistic regression performed better overall and was selected as the primary
model for churn risk prediction.

## Key Insights
- Customers on month-to-month contracts have significantly higher churn risk
- Short tenure customers are more likely to churn
- Higher monthly charges are associated with increased churn
- Long-term contracts and support services reduce churn risk

## Business Value
The model enables the business to:
- Identify high-risk customers early
- Prioritize retention efforts
- Reduce revenue loss through targeted interventions

