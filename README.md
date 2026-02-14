# Customer-churn-prediction-in-telecom-sector-using-machine-learning-techniques-
Customer churn prediction in telecom sector using machine learning techniques - Random Forest, SVM Classifier, Decision tree, XGboost, Naivebyes.
Customer Churn Prediction in Telecom Sector
This project implements various Machine Learning techniques to predict customer churn for a telecommunications company. By identifying customers at risk of leaving, the company can take proactive measures to improve retention.
📊 Project Overview
Predicting churn is a classic binary classification problem. This project compares five different algorithms to determine which provides the best balance of Accuracy, Precision, and Recall.
Key Features
Data Preprocessing: Handling missing values and categorical encoding.
Handling Imbalance: Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the churn vs. non-churn classes.
Visualizations: Confusion Matrices and ROC-AUC curves for model comparison.
🤖 Models Implemented
We evaluated the following algorithms:
Random Forest (Best Accuracy: ~77%)
XGBoost (Strongest competitor)
SVM (Support Vector Machine)
Decision Tree
Naive Bayes (High Recall for churn detection)



📈 Performance Summary
Model	Accuracy	Precision	Recall	F1-Score
Random Forest	77.3%	0.57	0.58	0.58
XGBoost	76.5%	0.56	0.59	0.57
SVM	74.6%	0.52	0.74	0.61
Naive Bayes	70.5%	0.47	0.81	0.59
Decision Tree	71.1%	0.46	0.57	0.51





🚀 Future Work to Hit 90% Accuracy
Hyperparameter Tuning: Use GridSearchCV to optimize XGBoost parameters.
Feature Engineering: Create behavioral features like MonthlyCharges_to_Tenure ratio.
Ensemble Learning: Implement a VotingClassifier to combine the strengths of RF, XGB, and SVM.
Author: Prashant Maurya
Dataset Source: Telco Customer Churn (Kaggle)
