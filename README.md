# Diabetes-Predictor
Built a diabetes predictor using patient health data. Compared multiple ML models to find what works best. Includes data analysis, model tuning, and evaluation.
Diabetes Prediction Using Machine Learning
A comprehensive machine learning project that predicts diabetes diagnosis based on medical diagnostic measurements. This project implements and compares multiple classification algorithms to identify the best-performing model.
📋 Table of Contents

Overview
Dataset
Features
Technologies Used
Model Performance
Installation
Usage
Project Structure
Results
Future Improvements

🎯 Overview
This project analyzes a diabetes prediction dataset and builds multiple machine learning models to predict whether a patient has diabetes based on diagnostic measurements. The project employs various classification algorithms with hyperparameter tuning to achieve optimal performance.
Key Highlights:

Comprehensive exploratory data analysis (EDA)
Implementation of 7 different ML algorithms
Hyperparameter tuning using GridSearchCV
Cross-validation with stratified K-fold
Feature scaling for optimal model performance

📊 Dataset
Source: Diabetes Prediction Dataset
Size: 1,000 samples
Features: 8 medical diagnostic measurements
Target: Binary classification (0 = No Diabetes, 1 = Diabetes)
Features Description:

Pregnancies: Number of times pregnant
Glucose: Plasma glucose concentration
BloodPressure: Diastolic blood pressure (mm Hg)
SkinThickness: Triceps skin fold thickness (mm)
Insulin: 2-Hour serum insulin (mu U/ml)
BMI: Body mass index (weight in kg/(height in m)^2)
DiabetesPedigreeFunction: Diabetes pedigree function (genetic influence)
Age: Age in years

✨ Features

Data Preprocessing: Handled missing values and standardized features
Exploratory Data Analysis: Statistical analysis and visualization
Multiple ML Models: Implemented 7 classification algorithms
Hyperparameter Tuning: GridSearchCV for optimal parameters
Cross-Validation: 5-fold stratified cross-validation
Model Comparison: Systematic evaluation of all models
