# Predicting Diabetic Readmission
**Goal:** Classify diabetic patients at risk of readmission within 30 days of hospital discharge.

## Description:
This project utilized the Diabetes 130-Hospitals dataset to develop machine learning models predicting the likelihood of patient readmission. The workflow included data preprocessing, addressing class imbalance using SMOTE, and evaluating several predictive models.

## Key Features:
- Implemented a data preprocessing pipeline to clean and balance the dataset.
- Applied machine learning models like Random Forest, XGBoost, and CatBoost.
- Conducted feature importance analysis to identify key predictors.

## Key Findings:
- Random Forest was the most effective model with an AUC score of 94% and recall of 88%.
- Top predictors included the number of lab procedures, number of medications, and hospital stay duration.

## Tools and Techniques:
- **Tools:** Python, Scikit-learn, Imbalanced-learn
- **Techniques:** SMOTE, Feature Importance Analysis, Model Evaluation
