# Credit Risk Analysis: Predicting Default Patterns

## Project Overview

This project builds machine learning models to predict whether a credit card customer will default on their next payment.

The analysis uses historical customer financial and repayment data to identify high-risk customers and evaluate predictive model performance.

---

## Dataset
Dataset used: **Default of Credit Card Clients Dataset**

Source:
https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients

Contains:
- Customer demographics
- Credit limits
- Bill statements
- Repayment history
- Default labels

**Records:** 30,000 customers  
**Features:** 25 variables  
**Target Variable:** `default payment next month`

---

## Tools Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## Machine Learning Objective

Build classification models to answer:

> Can we predict whether a customer will default next month based on their financial and repayment history?

This project compares multiple machine learning algorithms to determine the most effective model for default prediction.

Models used:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest Classifier

Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Workflow

1. Load cleaned dataset
2. Feature selection and target definition
3. Train-test split
4. Feature scaling using StandardScaler
5. Train classification models
6. Evaluate model performance
7. Compare results
8. Generate business insights

---

## Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

These metrics help measure both overall performance and the model's ability to correctly identify defaulters.

---

## Model Performance

| Model | Accuracy |
|---|---|
| Logistic Regression | 81% |
| KNN Classifier | 79% |
| Random Forest | 82% |

**Best Model:** Random Forest achieved the highest overall predictive performance.

---

## Key Insights

- Repayment behavior is the strongest predictor of customer default.
- Customers with multiple delayed payments are significantly more likely to default.
- Lower credit limits are associated with higher default risk.

---

## Business Recommendations

Banks can use predictive models like this to:

- Flag customers with repayment delays early
- Improve credit scoring decisions
- Monitor high-risk customer segments more closely
- Reduce financial losses from defaulting customers

---


## Project Structure

```bash
credit-risk-analysis-pandas/
│
├── README.md                   # Project documentation
├── credit-risk-ml.ipynb  # Main machine learning notebook

```

---

## View Full Notebook
[Open Notebook](./credit-risk-ml.ipynb)
