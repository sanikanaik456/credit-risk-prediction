# credit-risk-prediction
"Credit Risk Prediction using Machine Learning | Python, Scikit-learn, Random Forest | 149,999 records | ROC-AUC 0.837 | Feature Engineering &amp; EDA"
# Credit Risk Prediction 🏦

## Project Overview
Machine learning project to predict credit default risk using a dataset of 149,999 real-world borrower records. Built and evaluated multiple classification models to identify customers likely to experience serious financial delinquency within 2 years.

## Results
| Model | ROC-AUC Score |
|---|---|
| Logistic Regression | 0.69 |
| Random Forest | 0.714 |
| Random Forest (Balanced) | 0.837 |

**Best Model: Random Forest with Balanced Classes — ROC-AUC 0.837**

## Key Findings
- Revolving credit utilisation is the strongest predictor of default (20.7% importance)
- Engineered feature TotalLatePayments ranked 2nd most important (11%)
- Dataset is imbalanced (6.7% default rate) — handled using class_weight balancing
- 17% improvement in ROC-AUC achieved through class balancing technique

## Tech Stack
- Python, Pandas, NumPy
- Scikit-learn (Logistic Regression, Random Forest)
- Matplotlib, Seaborn
- Jupyter Notebook

## Project Structure
- credit_risk_analysis.ipynb — Full analysis notebook
- /images — EDA and model visualisations

## Dataset
Give Me Some Credit — 149,999 borrower records, 11 features
Source: Kaggle
