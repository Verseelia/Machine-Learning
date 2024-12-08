# Credit Card Approval Prediction

## Project Overview

This project focuses on predicting credit card approval decisions based on a variety of applicant attributes and historical credit data. The goal is to build a machine learning model that can automate the decision-making process for banks, reducing manual labor and minimizing the risk of loan defaults. This model will help financial institutions efficiently evaluate credit applications and identify eligible customers.

## Problem Statement

The task is to develop a predictive model that can determine whether a credit card application should be approved or rejected based on various features such as the applicant's income, education, family status, employment history, and credit record. The model will assist banks in making informed decisions while minimizing the risk of defaults and improving profitability.

### Objective

The main objectives of the project are:
- Perform **Exploratory Data Analysis (EDA)** to understand the dataset.
- Build and train multiple classification models (Random Forest, K-Nearest Neighbors, Gradient Boosting) to predict credit card approval.
- Develop a **meta-model** using Logistic Regression to combine the outputs of base models and enhance performance.
- Evaluate and compare the performance of the models using appropriate metrics.

## Dataset

The dataset consists of two CSV files:
- **Application Record.csv**: Contains data related to the applicants' personal and financial information.
- **Credit Record.csv**: Contains data on applicants' credit histories over time, indicating the status of their loans.

The columns in the dataset include details such as applicant demographics (age, gender), financial information (income, car ownership), employment history, credit status, and more.

## Data Preprocessing

1. **Handling Missing Data**: Missing values in certain columns were imputed or removed.
2. **Feature Engineering**: Derived additional features from available data such as age and employment history.
3. **Encoding**: Categorical variables were encoded using techniques like One-Hot Encoding or Label Encoding.
4. **Scaling**: Numerical features were scaled using StandardScaler to improve model performance.

## Machine Learning Models

### Base Models:
1. **Random Forest (RF)**: An ensemble method based on decision trees.
2. **K-Nearest Neighbors (KNN)**: A classification algorithm based on feature similarity.
3. **Gradient Boosting (GB)**: An advanced ensemble method that builds a model by combining multiple weak learners.

### Meta Model:
- **Logistic Regression (LR)**: A meta-model used to combine the predictions from base models and enhance performance. The logistic regression model was trained on the output of the base models to predict credit card approval.

## Model Evaluation

The models were evaluated using the following metrics:
- **Accuracy**: The percentage of correct predictions.
- **Precision, Recall, F1-Score**: These metrics evaluate the model's ability to predict positive and negative outcomes.
- 

## Steps Involved

1. **Data Exploration**: Perform EDA to understand the distribution of features, relationships between variables, and detect missing data.
2. **Model Training**: Train base models (RF, KNN, and GB) using the training data.
3. **Meta Model**: Combine the outputs from base models using Logistic Regression to improve the final model’s predictions.
4. **Model Comparison**: Compare the performance of individual models and the meta-model to determine the best model.




