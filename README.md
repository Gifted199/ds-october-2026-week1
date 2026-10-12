# Telecom Customer Churn Prediction

## 1. Problem Statement

Customer churn is a major challenge for telecommunications companies, as customers may leave for competitors offering better prices, services, or customer experiences. Losing customers can negatively affect revenue and increase the cost of acquiring new customers.

The challenge is that companies cannot always identify which customers are most likely to leave before they make that decision. Without this insight, retention efforts may be directed towards customers who are unlikely to churn, while customers at greater risk of leaving may be overlooked.

This project aims to address this challenge by applying machine learning techniques to historical telecommunications customer data to predict customer churn. By analysing customer characteristics, service subscriptions, contract types, and payment methods, the project seeks to identify patterns associated with customer churn and evaluate how effectively different classification models can predict whether a customer is likely to leave.

The ultimate goal is to provide data-driven insights that can help a telecommunications company identify at-risk customers, prioritise retention efforts, and make more informed business decisions.

## 2. Project Objectives

The main objectives of this project are to:

* Explore and understand the customer dataset.
* Clean the data and prepare it for machine learning.
* Perform exploratory data analysis (EDA) to identify patterns and factors associated with customer churn.
* Select relevant features for predicting churn.
* Build and evaluate multiple machine learning classification models.
* Compare model performance using accuracy, precision, recall, F1-score, and ROC-AUC.
* Identify a suitable model for predicting customers who are likely to churn.
* Recommend how the resulting insights could support customer retention strategies.

## 3. Dataset

This project uses a telecommunications customer churn dataset containing **7,043 customer records and 21 columns**.

The dataset includes information about customer services, contracts, payment methods, account characteristics, and churn status.

The target variable is `Churn`, which indicates whether a customer has left the company.

**Dataset source:** [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## 4. Business Value

The project aims to demonstrate how machine learning can support customer retention by helping businesses identify customers at risk of leaving.

Rather than treating every customer equally, a company could use churn predictions to prioritise customers for further investigation and targeted retention initiatives.

The model's predictions should be validated before being used in business operations, and the effectiveness of any retention strategy should be measured through an appropriate pilot.