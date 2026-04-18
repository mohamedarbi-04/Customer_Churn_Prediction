# Customer_Churn_Prediction
 Customer Churn Prediction

This project focuses on predicting customer churn using machine learning techniques. The goal is to analyze customer behavior and build a model capable of identifying customers likely to leave a service.

 Overview

Customer churn is a critical problem for businesses. In this project, we:

Perform data preprocessing and cleaning
Conduct exploratory data analysis (EDA)
Handle class imbalance
Train and evaluate multiple machine learning models
Build a prediction system for real-world use
 Technologies Used
Programming Language: Python
Libraries: Pandas, NumPy, Scikit-learn
Visualization: Matplotlib, Seaborn
Other Tools: SMOTE, Pickle
 Project Workflow
1. Data Preprocessing
Removed irrelevant features (e.g., customer ID)
Handled missing and inconsistent values
Encoded categorical variables using Label Encoding
2. Exploratory Data Analysis (EDA)
Analyzed distributions of numerical features
Visualized categorical variables
Identified correlations using heatmaps
Detected class imbalance in the target variable
3. Handling Imbalanced Data
Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset
4. Model Training
Trained multiple models:
Decision Tree
Random Forest
XGBoost (tested but not selected)
Used cross-validation to evaluate performance
5. Model Evaluation
Evaluated using:
Accuracy score
Confusion matrix
Classification report
Selected Random Forest as the best-performing model
6. Model Deployment
Saved the trained Random Forest model using Pickle
Built a simple prediction system for new input data
 Results
Random Forest achieved the best performance among tested models
Improved prediction accuracy by addressing class imbalance
Successfully built a reusable churn prediction system
 Key Skills Demonstrated
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Machine Learning Model Development
Handling Imbalanced Data
Model Evaluation & Optimization
 Future Improvements
Hyperparameter tuning for Random Forest
Deployment as a web application
Integration with real-time data pipelines
