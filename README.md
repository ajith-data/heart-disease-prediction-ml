# Heart Disease Prediction Using Machine Learning and PCA

## Project Overview

This project aims to predict the presence of heart disease using Machine Learning techniques. The dataset contains various clinical and health-related attributes of patients. The project follows a complete Machine Learning workflow, including data preprocessing, outlier detection, feature encoding, feature scaling, model training, dimensionality reduction using PCA, model evaluation, and performance comparison.

## Problem Statement

Heart disease is one of the leading causes of death worldwide. Early prediction can help healthcare professionals identify high-risk patients and take preventive measures. The objective of this project is to build and evaluate machine learning models that can accurately predict heart disease based on patient health data.

## Dataset

The dataset contains patient health information such as:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-Induced Angina
* Oldpeak
* ST Slope
* Heart Disease (Target Variable)

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* SciPy
* Scikit-learn
* Principal Component Analysis (PCA)
* Machine Learning

## Project Workflow

1. Data Loading and Exploration
2. Data Cleaning and Validation
3. Outlier Detection and Removal using Z-Score
4. Categorical Feature Encoding using Label Encoding
5. Train-Test Split
6. Feature Scaling using StandardScaler
7. Model Training

   * Logistic Regression
   * Support Vector Machine (SVM)
   * Random Forest
8. Model Evaluation

   * Accuracy Score
   * Precision
   * Recall
   * F1-Score
   * Confusion Matrix
   * ROC-AUC Score
9. Dimensionality Reduction using PCA
10. Model Retraining with PCA Features
11. Performance Comparison Before and After PCA
12. Feature Importance Analysis
13. Cross-Validation

## Machine Learning Models

### Logistic Regression

A linear classification algorithm used as a baseline model.

### Support Vector Machine (SVM)

A powerful classification algorithm that finds the optimal decision boundary between classes.

### Random Forest

An ensemble learning technique that combines multiple decision trees for improved prediction performance.

## Principal Component Analysis (PCA)

Principal Component Analysis (PCA) was applied to reduce dimensionality while retaining 95% of the dataset variance. The performance of machine learning models was evaluated before and after PCA to analyze the impact of dimensionality reduction.

## Evaluation Metrics

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC Score
* Cross-Validation Score

## Results

The performance of Logistic Regression, Support Vector Machine (SVM), and Random Forest models was compared before and after applying PCA. Random Forest achieved the best overall performance for heart disease prediction.

## Key Insights

* Data preprocessing significantly improved model quality.
* Feature scaling was essential for Logistic Regression and SVM.
* PCA successfully reduced feature dimensions while preserving most information.
* Random Forest provided the highest prediction accuracy.
* Feature importance analysis identified the most influential health indicators contributing to heart disease prediction.

## Project Structure

heart-disease-prediction-ml/

├── Heart_Disease_Prediction_With_PCA.ipynb

├── heart.csv

├── README.md

├── requirements.txt

└── images/

    ├── target_distribution.png

    ├── model_comparison.png

    ├── pca_variance.png

    ├── confusion_matrix.png

    ├── roc_curve.png

    └── feature_importance.png

## Future Improvements

* Hyperparameter tuning using GridSearchCV
* Deployment using Streamlit or Flask
* Integration with cloud platforms
* Real-time patient risk prediction dashboard

## Author

Ajith B

Aspiring Data Analyst | Python | SQL | Power BI | Machine Learning
