# Fraudulent Transaction Detection
The primary objective is to identify fraudulent transactions. The project explores both supervised learning (Logistic Regression and XGBoost) and unsupervised learning (Isolation Forest) techniques. It demonstrates handling data imbalance using SMOTE and showcases explainability using feature importance and SHAP.

## Contents
1. Project Overview
2. Setup Instructions
3. Data Exploration and Preprocessing
4. Model Development
    - Supervised Models
    - Unsupervised Models
5. Evaluation
6. Explainability
7. Results

1) Data Exploration and Preprocessing
Key Steps:

## Statistical Analysis:
- Descriptive statistics were generated for each feature.

## Data Visualization:
- Histograms and boxplots for feature distributions.
- Correlation matrix for feature relationships.
- Target class distribution analysis.

## Missing Values:
- Verified no missing values.

## Scaling:
- Standardized features (V1, V2, V3) using StandardScaler.

## Imbalance Handling:
- Applied SMOTE to balance the class distribution.

2) Model Development

## Supervised Models
- Logistic Regression - baseline classification model for binary classification.
- XGBoost - Gradient Boosting framework optimized with RandomizedSearchCV for hyperparameter tuning.

## Unsupervised Models
- Isolation Forest:
Anomaly detection algorithm for identifying fraudulent transactions.

3) Model Evaluation
 1) Supervised Model Metrics:
- Classification Report: Precision, recall, F1-score.
- Confusion Matrix: Visualized to assess performance on fraud detection.
- ROC-AUC and PR-AUC Curves: Evaluate model performance for imbalanced data.

 2) Unsupervised Model Metrics:
 - Anomaly Detection: Compared detected anomalies against known fraudulent transactions.

 4) Explainability
- Feature Importance:
Used XGBoost's plot_importance for feature rankings.

- SHAP Values:
Provided a comprehensive understanding of feature contributions to predictions.

5) Results

- Supervised Models:
Logistic Regression:
Baseline performance established.

- XGBoost:
Achieved improved precision and recall after hyperparameter tuning.

- Unsupervised Models:
Isolation Forest identified anomalies with a contamination rate of 0.01.

- Explainability:
SHAP and feature importance highlighted key variables influencing model predictions.











