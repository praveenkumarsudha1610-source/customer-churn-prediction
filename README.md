
# Customer Churn Prediction

## Project Overview
This project uses machine learning to predict whether a telecom
customer is likely to leave the service (churn).

## Dataset
IBM Telco Customer Churn dataset containing customer demographics,
services, contract details, charges, and churn status.

## Work Completed
- Data inspection and cleaning
- Exploratory Data Analysis (EDA)
- Missing-value handling
- Categorical feature encoding
- Numerical feature scaling
- Logistic Regression
- Random Forest
- Model evaluation and comparison
- Feature importance analysis

## Models Evaluated
- Logistic Regression
- Logistic Regression with a 0.4 classification threshold
- Random Forest

## Best Current Candidate
Logistic Regression with a 0.4 threshold.

- Accuracy: 77.71%
- Churn Precision: 56.82%
- Churn Recall: 66.84%
- Churn F1-score: 0.6143

The model and threshold were selected based on the current test-set
results. Further validation may be needed before production use.

## Tools and Technologies
Python, Pandas, NumPy, Matplotlib, Scikit-learn, Jupyter Notebook

## Project Structure
- data/: Dataset
- models/: Saved model, preprocessor, and threshold
- reports/: Project reports and visualizations
- Customer_Churn_Prediction.ipynb: Main project notebook
