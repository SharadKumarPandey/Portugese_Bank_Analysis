# Portugese_Bank_Analysis

This project analyzes a Portuguese bank marketing dataset to predict whether a client will subscribe to a term deposit. Using machine learning techniques, the project performs data preprocessing, exploratory data analysis, and model training to identify patterns in customer behavior and improve marketing campaign effectiveness.

---------------------------

Problem Statement

Banks conduct marketing campaigns to promote term deposit subscriptions. However, contacting every customer is costly and inefficient.

The goal of this project is to build a predictive model that identifies customers who are more likely to subscribe to a term deposit, allowing banks to target the right audience.

----------------------

Dataset Information

The dataset contains information about clients contacted during marketing campaigns conducted by a Portuguese bank.

Key Features

Age – Age of the client

Job – Type of job

Marital Status – Married, single, divorced

Education – Level of education

Balance – Average yearly balance

Housing Loan – Whether the client has a housing loan

Personal Loan – Whether the client has a personal loan

Contact – Communication type

Campaign – Number of contacts during the campaign

Previous Outcome – Outcome of previous campaign

Target Variable

y

yes → Client subscribed to term deposit

no → Client did not subscribe

----------------------

Project Workflow

1. Data Preprocessing

Steps performed:

Handling missing values

Encoding categorical variables

Feature scaling

Data cleaning

2. Exploratory Data Analysis (EDA)

EDA was performed to understand relationships between variables.

Key analysis included:

Age distribution

Job category analysis

Campaign success rate

Correlation between features

Machine Learning Models Used

The following models were implemented:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Naive Bayes

These models were trained to predict whether a client will subscribe to a term deposit.

Model Evaluation Metrics

Models were evaluated using:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

These metrics help determine how well the model predicts customer subscription behavior.

------------------------

Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

--------------------------

Key Insights

Certain job categories have higher subscription rates.

Customers with higher balances are more likely to subscribe.

Previous successful campaigns increase the likelihood of future subscriptions.

------------------------------

Future Improvements

Possible enhancements:

Hyperparameter tuning

Feature engineering

Using advanced models like XGBoost

Deploying the model as a web application
