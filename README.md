# Risky_credit_applicant

## Introduction
With the increasing prevalence of digital transactions, credit cards have become not only a popular payment method but also a representation of users' creditworthiness. Managing credit card approvals is essential for financial institutions to minimize risks associated with unpaid debts. In this project, we present an approach to refine the credit card approval process using advanced machine learning algorithms that prioritize predictive accuracy and model transparency.

## Dataset
The dataset used in this project is the Credit Card Approval Prediction dataset from [Kaggle](https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction). It includes client records for a financial service, containing various features such as demographics, income, education, and employment history. Additionally, a dataset with monthly financial account records linked to clients is provided, indicating account statuses and payment behaviors.

## Exploratory Data Analysis (EDA)
During EDA, we explored correlations between features and identified key demographic and financial trends among credit card applicants. Data cleaning involved handling missing values, outliers, and classifying applicants into 'good' and 'bad' credit categories based on overdue payments.

## Data Preparation
Data preparation involved feature engineering, encoding categorical variables, imputing missing values, and addressing class imbalance using Synthetic Minority Over-sampling Technique (SMOTE).

## Modeling Methodologies
We evaluated various machine learning models, including logistic regression, decision trees, random forest, gradient boosting machines (GBM), support vector machines (SVM), and neural networks. First we created a baseline model using AutoML and then proceeded with Random Forest as our finalized model. Both traditional and complex models were assessed to balance predictive accuracy and interpretability.

## Results and Findings
Among the models evaluated, random forest and neural network showed superior performance in terms of recall, precision, and F1 scores. Adjustments such as introducing class weights and modifying decision thresholds were made to improve model performance further. We also investigated the fairness of our model and found that it does not particularly discriminates based on gender or marital status.

## Discussion
Challenges encountered included the precision-recall trade-off due to imbalanced datasets. Model fairness was assessed using demographic parity metrics, indicating a slight favor towards female applicants in credit card approval.
