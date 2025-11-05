# Kaggle Superstore Marketing Campaign

This project builds and analyzes a **logistic regression model** to predict which customers are most likely to respond to a marketing campaign. 

---

## Project Overview

### Business Context
The marketing team wanted to promote a discounted Gold Membership — offering a 20% discount on all purchases for $499 (down from $999). To minimize campaign costs, leadership requested a predictive model to classify which existing customers were most likely to purchase the offer.

### Objectives
- Predict the likelihood of a customer purchasing the Gold Membership
- Identify key features that drive positive purchase responses
- Generate a prioritized call list of high-potential customers for the outbound campaign

---

## Dataset

The dataset used is the **Superstore Marketing Campaign** dataset available on [Kaggle](https://www.kaggle.com/datasets/ahsan81/superstore-marketing-campaign-dataset).

Key columns include:
- **Age**, **Income**, **Marital Status**, **Education**, **Recency**, **NumWebPurchases**, **NumStorePurchases**, **Response** (target)

The target variable `Response` indicates whether a customer responded to a previous campaign (1 = Yes, 0 = No).

---

## Project Steps

1. **Exploratory Analysis** — Assessed demographic, behavioral, and spending trends among customers.  
2. **Data Cleaning** — Addressed missing values, encoded categorical variables, and normalized features.  
3. **Feature Engineering** — Created variables representing engagement and past purchase activity.  
4. **Data Splitting** — Divided the dataset into training and test sets for model evaluation.  
5. **Model Training** — Built a logistic regression model to classify positive responses.  
6. **Optimization** — Tuned hyperparameters and evaluated feature importance.  
7. **Reporting** — Exported predictions and insights to feed a Looker Studio dashboard.

---

## Technologies Used

| Category | Tools |
|-----------|-------|
| Programming | Python 3.10 |
| Data Analysis | pandas, numpy |
| Visualization | matplotlib, seaborn |
| Machine Learning | scikit-learn |
| Notebook | Jupyter Lab / Notebook |

---

## Results Summary

The logistic regression model achieved an accuracy of ~XX% (replace with your final number).

Key predictors of campaign response include Recency, Income, and Total Purchases.

Model insights helped identify actionable segments for targeted marketing.

---

## View the Notebook

You can view the full analysis (here)[google.com]

---

## Author

Katie DelValle
Product Marketing Analyst | Data Storyteller
(analyst-katied.github.io)[analyst-katied.github.io]