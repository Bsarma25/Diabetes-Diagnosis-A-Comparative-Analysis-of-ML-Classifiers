# Diabetes Prediction
## Overview
A supervised machine learning project focused on binary classification to predict diabetes risk. Utilizes CDC data from Kaggle with over 250,000 patients and 22 features, including health and lifestyle factors.
## Data Preprocessing

- Checked for missing values; dataset had none.
- Removed duplicate rows.
- Normalized the data and performed an 80:20 train-test split.
## Feature Selection
- Conducted a chi-squared test to select features based on their scores.
## Handling Imbalanced Data
- Applied undersampling and SMOTE to address data imbalance.
## Model Building and Evaluation
- Experimented with various ML algorithms including Logistic Regression, KNN, SVM, and Random Forest.
- Random Forest achieved the best performance, with a recall of 0.89.
