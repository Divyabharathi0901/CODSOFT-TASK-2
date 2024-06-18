CODSOFT TASK -2: Customer Churn Prediction for Subscription-Based Services

This repository contains a comprehensive project aimed at predicting customer churn for a subscription-based service using historical customer data. The project leverages various machine learning algorithms, including Logistic Regression, Random Forest, and Gradient Boosting, to develop and optimize predictive models.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Description](#data-description)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
4. [Feature Engineering](#feature-engineering)
5. [Modeling](#modeling)
6. [Hyperparameter Tuning](#hyperparameter-tuning)
7. [Results](#results)

## Introduction
Customer churn is a critical issue for subscription-based businesses as retaining customers is often more cost-effective than acquiring new ones. This project aims to predict which customers are likely to churn using machine learning techniques. By understanding the factors leading to churn, businesses can take proactive measures to improve customer retention.

## Data Description
The dataset used in this project includes historical customer data with features such as usage behavior and customer demographics. The key features in the dataset include:
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary
- Exited (Target variable indicating whether the customer churned)

## Exploratory Data Analysis (EDA)
The EDA section provides insights into the dataset, including:
- Basic statistics and data structure
- Distribution of numerical and categorical features
- Correlation matrix to understand feature relationships
- Class balance analysis

## Feature Engineering
This section includes preprocessing steps such as:
- Dropping unnecessary columns
- Encoding categorical variables using one-hot encoding
- Scaling numerical features for model training

## Modeling
The modeling section covers the implementation of three machine learning algorithms:
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

Each model is trained, and its performance is evaluated using appropriate metrics.

## Hyperparameter Tuning
To improve model performance, hyperparameter tuning is conducted using RandomizedSearchCV. This helps in identifying the best parameters for Random Forest and Gradient Boosting models.

## Results
The results section presents the performance of each model using classification reports, highlighting precision, recall, f1-score, and accuracy.
