# Credit Scoring Model

## Project Overview

This project predicts whether a customer is likely to repay a loan using Machine Learning techniques.

The project was developed as part of the CodeAlpha Machine Learning Internship.

## Dataset

Credit Risk Dataset

Features include:

* Age
* Income
* Employment Length
* Home Ownership
* Loan Intent
* Loan Grade
* Loan Amount
* Interest Rate
* Credit History

## Feature Engineering

Two additional features were created:

* income_per_age
* loan_percent_income

## Models Implemented

1. Logistic Regression
2. Decision Tree
3. Random Forest

## Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 82.99%   |
| Decision Tree       | 88.71%   |
| Random Forest       | 92.80%   |

## Best Model

Random Forest achieved the highest accuracy and was selected as the final model.

Final Metrics:

* Accuracy: 92.80%
* Precision: 95.78%
* Recall: 70.66%
* F1 Score: 81.32%
* ROC-AUC: 93.71%

## Visualizations

* Confusion Matrix
* ROC Curve
* Feature Importance Plot

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Joblib

## Output

The trained model was saved as:

credit_model.pkl

## Author

Vivek Vipparla
CodeAlpha Machine Learning Internship
