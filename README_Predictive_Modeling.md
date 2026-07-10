# Predictive Modeling: Customer Churn Prediction

Data Science internship project — **Thiranex**

## About the Project

This project builds and compares machine learning models to predict **customer churn** — whether a customer is likely to stop using a service — based on their account details (age, tenure, monthly charges, contract type, support calls, and internet service type).

## What This Project Does

- Cleans raw customer data (missing values, duplicates)
- Encodes categorical features (Contract, InternetService) into numeric form
- Splits data into training and test sets
- Trains and compares **3 machine learning models**:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Evaluates each model using:
  - Accuracy score
  - Precision, recall, f1-score
  - Confusion matrix
  - ROC curve & AUC score
- Identifies the most important features driving churn predictions

## Tools & Libraries Used

- **Python**
- **Pandas / NumPy** – data handling
- **Scikit-learn** – machine learning models & evaluation metrics
- **Matplotlib / Seaborn** – visualization
- **Jupyter Notebook** (via Google Colab)

## Files in This Repo

| File | Description |
|---|---|
| `Predictive_Modeling_Churn.ipynb` | Main notebook — full ML pipeline with explanations and charts |
| `raw_customer_churn.csv` | Original raw dataset (before cleaning) |
| `cleaned_customer_churn.csv` | Cleaned dataset (after removing duplicates and missing values) |

## Key Results

- **Logistic Regression** achieved the highest accuracy (~71%) among the three models.
- **Contract type** and **Monthly Charges** were the strongest predictors of churn.
- All models performed meaningfully better than random guessing, confirmed by ROC/AUC analysis.

## How to Run

1. Open `Predictive_Modeling_Churn.ipynb` in [Google Colab](https://colab.research.google.com)
2. Upload `raw_customer_churn.csv` to the Colab session (Files panel → upload icon)
3. Run all cells (**Runtime → Run all**)

## Author

Submitted as part of a Data Science internship task at Thiranex.
