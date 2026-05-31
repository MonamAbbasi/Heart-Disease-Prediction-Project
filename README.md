Heart Disease Prediction Using Machine Learning

Project Overview

This project focuses on predicting the presence of heart disease using Machine Learning techniques. Multiple machine learning algorithms were implemented, trained, and evaluated to compare their performance and identify the most suitable model for heart disease prediction.

The project includes data preprocessing, feature engineering, categorical data encoding, feature scaling, model training, performance evaluation, and model comparison.

---

Dataset Information

Dataset Name: Heart Disease Dataset

Dataset Shape: 1000 Rows × 16 Columns

Features

- Age
- Gender
- Cholesterol
- Blood Pressure
- Heart Rate
- Smoking
- Alcohol Intake
- Exercise Hours
- Family History
- Diabetes
- Obesity
- Stress Level
- Blood Sugar
- Exercise Induced Angina
- Chest Pain Type

Target Variable

- Heart Disease
  - 0 = No Heart Disease
  - 1 = Heart Disease

---

Data Preprocessing

The following preprocessing techniques were applied:

Categorical Encoding

Label Encoding

Applied on binary categorical features:

- Gender
- Alcohol Intake
- Family History
- Diabetes
- Obesity
- Exercise Induced Angina

One-Hot Encoding

Applied on multi-category features:

- Smoking
- Chest Pain Type

Train-Test Split

- Training Data: 80%
- Testing Data: 20%

Feature Scaling

StandardScaler was applied before training:

- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

---

Machine Learning Algorithms Implemented

Regression Models

1. Simple Linear Regression
2. Multiple Linear Regression

Classification Models

3. Logistic Regression
4. Decision Tree Classifier
5. Random Forest Classifier
6. K-Nearest Neighbors (KNN)
7. Support Vector Machine (Linear Kernel)
8. Support Vector Machine (Polynomial Kernel)
9. Support Vector Machine (RBF Kernel)

---

Model Performance

Regression Results

Model| Score
Simple Linear Regression| R² = 0.43
Multiple Linear Regression| R² = 0.58

Classification Results

Model| Accuracy
Logistic Regression| 87%
Decision Tree| 100%
Random Forest| 100%
KNN (Best K = 15)| 72.5%
SVM (Linear Kernel)| 86%
SVM (Polynomial Kernel)| 80%
SVM (RBF Kernel)| 86%

---

Feature Analysis

Correlation Analysis

The strongest correlations with Heart Disease were:

Feature| Correlation
Age| 0.646
Cholesterol| 0.365

Feature Importance (Tree-Based Models)

The most influential features were:

Feature| Importance
Age| 0.543
Cholesterol| 0.271

These results indicate that Age and Cholesterol are the most important predictors of heart disease in this dataset.

---

Key Findings

- Age showed the strongest relationship with heart disease.
- Cholesterol was the second most influential feature.
- Multiple Linear Regression performed better than Simple Linear Regression.
- Logistic Regression achieved strong classification performance with 87% accuracy.
- KNN produced the lowest accuracy among all classification models.
- Decision Tree and Random Forest achieved the highest accuracy of 100%.
- Linear SVM demonstrated excellent generalization with very similar training and testing accuracy.
- Polynomial SVM showed signs of overfitting due to a large gap between training and testing accuracy.
- RBF SVM performed better than Polynomial SVM but did not outperform Linear SVM on the test set.

---

Model Comparison Summary

Best Accuracy

- Decision Tree: 100%
- Random Forest: 100%

Best Generalization

- Linear SVM
- Logistic Regression

Lowest Performance

- K-Nearest Neighbors (KNN)

---

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

Concepts Applied

- Data Preprocessing
- Label Encoding
- One-Hot Encoding
- Correlation Analysis
- Feature Scaling
- Train-Test Split
- Regression
- Classification
- Hyperparameter Tuning
- Model Evaluation
- Accuracy Comparison
---
Author
Monam Abbasi
BS Software Engineering
Machine Learning Project – Heart Disease Prediction
