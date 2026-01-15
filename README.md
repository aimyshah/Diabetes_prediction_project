# Diabetes Detection Project

## Project Overview
This project uses machine learning techniques to predict the likelihood of whether a patient is diabetic
based on important health features such as glucose level, BMI, insulin, blood pressure, age, and other 
related factors.

## Problem Statement
Diabetes has become a common health issue worldwide. Early detection of diabetes can help
prevent serious complications such as organ failure and cardiovascular diseases.
The goal of this project is to identify diabetic patients at an early stage so they can
seek medical attention or make lifestyle changes to manage the condition effectively.

## Dataset
This project uses the Pima Indians Diabetes Dataset, originally from the National Institute
of Diabetes and Digestive and Kidney Diseases and available on Kaggle. It includes 769 records
with health features (e.g., Pregnancies, Glucose, BloodPressure, BMI, Insulin, DiabetesPedigreeFunction, Age)
and the binary target label Outcome (1 = diabetic, 0 = non-diabetic).

## Approach
- Loaded and explored the dataset.
- Performed data preprocessing and standardization.
- Split the dataset into training and testing sets.
- Used cross-validation to select the best-performing machine learning model.
- Trained a Support Vector Machine (SVM) classifier.
- Evaluated the model using accuracy score.
- Built a prediction function to accept user input and predict diabetes.

### Why SVM?
This is a binary classification problem. SVM performs well in high-dimensional spaces and
is effective for datasets with clear class boundaries. Among the tested models, SVM
achieved the best performance on this dataset.

## Results
- **Training Accuracy:** 86.57%
- **Testing Accuracy:** 85.80%

