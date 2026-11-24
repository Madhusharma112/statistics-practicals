# Practical 8: Decision Tree Classification Using Pima Indians Diabetes Dataset

## Overview
This practical focuses on implementing a Decision Tree Classification model using the Pima Indians Diabetes dataset to predict whether a patient has diabetes based on medical measurements.

## Dataset
- **Dataset Name:** Pima Indians Diabetes Dataset
- **File Name:** `diabetes.csv`
- **Records:** 768
- **Features:** 8
- **Target Variable:** Outcome

## Key Analysis Performed
- Dataset loading and exploration
- Feature selection and train-test splitting
- Decision Tree Classification using Entropy
- Model prediction and evaluation
- Decision Tree visualization
- Root Node selection
- Entropy and Gini Index calculation
- Information Gain and Gini Gain calculation
- Information Gain and Gini Gain visualization
- Manual Information Gain calculation for root split

## Model Evaluation
- Accuracy
- Confusion Matrix
- Classification Report
- Precision, Recall and F1-score

## Key Findings
- Model accuracy: **80.52%**
- Glucose was selected as the root feature.
- Root threshold: **154.5**
- Glucose achieved the highest Information Gain and Gini Gain among the features.

## Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Conclusion
This practical demonstrates the working of Decision Tree Classification and explains how Entropy, Gini Index, Information Gain, and Gini Gain help in selecting the best features for classification.
