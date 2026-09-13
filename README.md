# Advancing Loan Approval Processes Through Explainable AI

## Project Overview

This project presents a machine learning-based loan approval system that predicts loan application outcomes and provides explanations for the model's decisions.

The system uses applicant and loan-related information to predict whether a loan application is approved or rejected. Explainable AI techniques are integrated to identify the important factors that influence the prediction, making the results easier to understand.

## Key Features

- Loan approval status prediction using Machine Learning
- Loan rejection reason prediction
- Data preprocessing and feature normalization
- Random Forest classification
- Model performance evaluation using Accuracy, Precision, Recall, and F1-Score
- Confusion matrix visualization
- Explainable AI using SHAP
- Prediction on test data

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- SHAP
- Tkinter

## Machine Learning Model

The project uses the **Random Forest Classifier** to predict:

1. Loan application status
2. Loan rejection reason

The dataset is divided into training and testing sets using an 80:20 ratio.

## Explainable AI

**SHAP (SHapley Additive exPlanations)** is used to explain the predictions made by the Random Forest model.

The SHAP analysis helps identify which features have the greatest influence on the model's predictions, improving the transparency and interpretability of the loan approval process.

## Project Workflow

```text
Loan Application Dataset
          ↓
     Data Loading
          ↓
    Data Preprocessing
          ↓
    Feature Encoding
          ↓
   Feature Normalization
          ↓
    Train-Test Split
          ↓
   Random Forest Model
          ↓
     Prediction
          ↓
   Model Evaluation
          ↓
     SHAP Analysis
          ↓
  Explainable Prediction
