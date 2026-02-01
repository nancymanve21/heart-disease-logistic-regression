# Heart Disease Prediction using Logistic Regression

This project implements a machine learning pipeline to predict the presence of heart disease using Logistic Regression. The workflow includes data exploration, cleaning, outlier handling, feature scaling, model training, and performance evaluation.

## 📌 Project Overview
Heart disease is a major health concern worldwide. This project aims to build a classification model that predicts whether a patient has heart disease based on medical attributes using Logistic Regression.

## 🗂 Dataset
- Heart disease dataset (CSV format)
- Contains medical and demographic features
- Target variable indicates presence or absence of heart disease

## 🔧 Steps Performed
- Imported and explored the dataset
- Checked for missing values and duplicate records
- Removed duplicate rows
- Detected and removed outliers using the IQR method
- Split data into training and testing sets
- Applied Standard Scaling to numerical features
- Trained a Logistic Regression model
- Evaluated model performance using:
  - Accuracy
  - Precision
  - F1-score
  - Confusion Matrix

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn

## 📊 Model Used
- Logistic Regression

## ✅ Key Learnings
- Importance of data cleaning and preprocessing
- Effect of outliers and feature scaling on model performance
- Evaluation of classification models using multiple metrics

## 🚀 Future Improvements
- Try alternative models (Decision Tree, Random Forest)
- Use RobustScaler instead of outlier removal
- Perform hyperparameter tuning
- Optimize for recall (important for medical datasets)

## 📁 File
- `LogisticRegression.ipynb` – Complete implementation notebook
