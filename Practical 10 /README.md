# Practical 10: Exploratory Data Analysis, Feature Scaling, and PCA Using the Wine Dataset

## Overview
This practical focuses on Exploratory Data Analysis (EDA), feature scaling, covariance analysis, and Principal Component Analysis (PCA) using the Wine dataset. It explores chemical characteristics of wines from three different cultivars and applies dimensionality reduction to visualize class separation.

## Dataset Information
- **Dataset Name:** Wine Dataset
- **Observations:** 178
- **Features:** 13 chemical attributes
- **Target Variable:** Class
- **Classes:** 3 wine cultivars (1, 2, and 3)

## Key Analysis Performed
- Basic descriptive statistics using `describe()`
- Class-wise distribution analysis using boxplots
- Bivariate analysis using scatterplots
- Covariance matrix calculation and visualization
- Feature scaling using StandardScaler
- Comparison of raw and standardized covariance matrices
- Principal Component Analysis (PCA)
- 2D PCA visualization and Scree Plot

## Key Findings
- The dataset contains 178 observations and 13 chemical features.
- Feature scaling eliminates differences caused by varying measurement scales.
- Flavanoids and Total Phenols show a strong positive correlation (r = 0.86).
- The first two principal components explain 55.4% of the total variance.
- PCA provides clear separation among the three wine classes.

## Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Conclusion
This practical demonstrates the importance of Exploratory Data Analysis and feature standardization in multivariate statistical analysis. PCA reduces the 13-dimensional dataset into two principal components while retaining 55.4% of the total variance, providing clear visualization and separation of the three wine cultivars.
