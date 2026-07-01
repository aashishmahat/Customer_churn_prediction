# Customer_churn_prediction


## Overview
This project predicts whether a telecom customer will churn (leave the company)
or not using Machine Learning. It helps companies identify at-risk customers 
early and take action to retain them.

## Dataset
- Source: Kaggle Telco Customer Churn
- Rows: 7043
- Columns: 21
- Target: Churn (Yes/No)

## Steps Followed
1. Exploratory Data Analysis (EDA)
2. Data Cleaning (TotalCharges object → numeric conversion)
3. One Hot Encoding (pd.get_dummies)
4. Feature Scaling (StandardScaler)
5. Model Building (KNN, SVM, Decision Tree)
6. Cross Validation (K-Fold, cv=5)


## Results
| Model | Precision | Recall | F1 Score |
|-------|-----------|--------|----------|
| SVM   | 68.4%     | 57.8%  |62.7%     |
| KNN   | 65.2%     | 57.6%  | 61.2     |
| Decision Tree | 47.1% | 45.7% | 46.4% |

## Best Model
SVM (Linear Kernel) — CV Accuracy: 79.88%

## Libraries
- Pandas, Numpy
- Matplotlib, Seaborn
- Scikit-learn

## How to Run
1. Clone the repo
2. pip install -r requirements.txt
3. Open churn.ipynb in Jupyter Notebook
