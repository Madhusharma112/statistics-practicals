# Practical 9: K-Nearest Neighbours (KNN) Classification Using the Iris Dataset

## Overview
This practical implements a K-Nearest Neighbours (KNN) classification model using the Iris dataset to predict flower species based on sepal and petal measurements.

## Dataset
- **Dataset Name:** Iris Dataset
- **Records:** 150
- **Features:** 4
- **Target Variable:** Species

## Key Analysis Performed
- Dataset loading and exploration
- Feature scaling using StandardScaler
- Training and testing data splitting (80:20)
- KNN classification with K = 5
- Confusion Matrix and Accuracy Score
- Classification Report
- Error Rate calculation for K values (1–30)
- Error Rate vs K visualization
- Best K Value selection
- Visualization of actual and predicted results

## Model Evaluation
- Accuracy: **93.33%**
- Minimum Error Rate: **3.33%**
- Best K Value: **7**

## Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Conclusion
The KNN classifier achieved 93.33% accuracy with K = 5. Error rates were compared for different K values, and K = 7 was selected from tied minimum-error candidates.
