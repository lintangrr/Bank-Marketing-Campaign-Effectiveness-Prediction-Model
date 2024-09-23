# Bank-Marketing-Campaign-Effectiveness-Prediction-Model
## Background
Term deposits are a popular financial product where customers deposit money in a bank for a fixed period .Term deposit investments usually carry short-term maturities ranging from one month to a few years and will have varying levels of required minimum deposits. To stay competitive and attract new customers, banks often run marketing campaigns to offer this term deposit product.
## Problem Statement
A bank wants to improve the effectiveness of its marketing campaigns by predicting whether a customer will invest to a term deposit based on a range of customer attributes and past marketing interactions.
## Goal
The project aims to build a classification model using historical data, which contains features such as customer demographics and previous campaign results to predict the likelihood of investment to term deposits. The key target variable is whether a customer subscribed to a term deposit (binary outcome: yes or no).
## Analytical Approach
1. Data Preparation:
   - Clean and preprocess the dataset, handling missing values and outliers.
   - Encode categorical variables and scale numerical features as necessary.
2. Classification Modeling:
   - Split the dataset into training and testing sets to evaluate model performance.
   - Use classification algorithms (e.g., logistic regression, decision trees, random forests, or gradient boosting).
   - Train the selected classification models on the training set and validate their performance on the testing set.
## Conclusion
Random Forest Classifier Model with Hyperparameter Tuning and Threshold Adjustment has the best performance (highest F1-Score) in predicting whether a customer will make a deposit or not after being contacted by the bank.
