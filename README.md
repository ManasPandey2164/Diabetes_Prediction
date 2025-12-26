# Diabetes Prediction Using Machine Learning

This project builds and evaluates multiple machine learning models to predict diabetes using patient health data.

## Dataset
- Source: Kaggle – Diabetes Prediction Dataset  
- Features include age, BMI, HbA1c, blood glucose, gender, smoking history, etc.

## Workflow
1. Data loading and cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature encoding & scaling  
4. Train-test split  
5. Model training and evaluation  
6. Model saving for deployment  

## Models Used
- Logistic Regression  
- Random Forest  
- K-Nearest Neighbors  
- Gradient Boosting  

## Evaluation Metrics
- Accuracy  
- ROC-AUC Score  
- Classification Report  

## Output
- Trained models saved as `.joblib`
- Scaler saved for future predictions

## How to Run
```bash
python diabetes_prediction.py
