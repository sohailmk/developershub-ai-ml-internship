# Task 3 — Heart Disease Prediction using Machine Learning

## Objective
The objective of this project is to build a machine learning model that predicts whether a patient has heart disease based on medical attributes.

## Dataset
UCI Heart Disease Dataset (CSV format)

Features include:
- age
- sex
- cp
- trestbps
- chol
- fbs
- restecg
- thalach
- exang
- oldpeak
- slope
- ca
- thal
- num (target column)

## Problem Type
Binary Classification:
- 0 → No heart disease
- 1 → Heart disease present

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Workflow
1. Load dataset
2. Clean data (handle "?")
3. Convert data to numeric
4. Handle missing values
5. Create binary target column from `num`
6. Exploratory Data Analysis (EDA)
7. Train-test split
8. Logistic Regression model training
9. Model evaluation

## Model Used
Logistic Regression (max_iter=1000)

## Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC Curve

## Results
The model is able to predict heart disease based on medical features with reasonable accuracy.

## Key Learnings
- Data cleaning and preprocessing
- Handling real-world messy datasets
- Binary classification modeling
- Model evaluation techniques

## Future Improvements
- Try Random Forest or XGBoost
- Hyperparameter tuning
- Deploy as web app using Streamlit or Flask