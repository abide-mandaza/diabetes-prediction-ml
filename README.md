# Diabetes Prediction Using Machine Learning

## Overview
This project focuses on predicting the likelihood of diabetes using machine learning techniques applied to healthcare data. The goal is to support early detection by leveraging patient health parameters and comparing the performance of multiple classification models.

## Dataset
1. Healthcare Diabetes Dataset (Kaggle)
2. Key features include:
   1. Pregnancies  
   2. Glucose  
   3. Blood Pressure  
   4. BMI  
   5. Insulin  
   6. Age  
   7. Diabetes Pedigree Function  
3. Target variable:
   1. Outcome (0 = Non-diabetic, 1 = Diabetic)

## Key Tasks & Methodology
1. Data cleaning and preprocessing (handling missing and zero values)
2. Exploratory Data Analysis (EDA) and visualization
3. Feature engineering (BMI and age grouping)
4. Handling class imbalance using class weights
5. Training and evaluating machine learning models

## Models Implemented
1. Logistic Regression (baseline)
2. Random Forest
3. K-Nearest Neighbors (KNN)
4. XGBoost

## Evaluation Metrics
1. Accuracy
2. Precision
3. Recall
4. F1-Score
5. ROC–AUC

## Results
1. Random Forest achieved the best performance:
   1. Accuracy ≈ 98%
   2. ROC–AUC ≈ 0.99
2. The results show that ensemble models are highly effective for diabetes prediction when combined with proper preprocessing and feature engineering.

## Tools & Technologies
1. Python
2. Pandas, NumPy
3. Matplotlib, Seaborn
4. Scikit-learn
5. XGBoost
6. Google Colab

## Notebook
1. [Predictive Analysis for Diabetes Dataset](Predictive_Analysis_for_Diabetes_Dataset.ipynb)`

## Author
**Abide Mandaza**  
GitHub: https://github.com/abide-mandaza
