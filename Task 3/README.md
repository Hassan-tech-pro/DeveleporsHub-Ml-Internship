# Task 3: Heart Disease Prediction

This project is part of the AI/ML Internship at DevelopersHub. The objective is to build a machine learning model to predict the presence of heart disease in patients based on various health metrics.

## Objective
To develop a classification model that can accurately identify whether a patient has heart disease based on clinical parameters like age, cholesterol levels, chest pain type, and maximum heart rate.

## Dataset
The project uses the **Heart Disease Dataset** from Kaggle.
- **Source**: `johnsmith88/heart-disease-dataset`
- **Features**: Includes 13 health-related attributes (age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal).
- **Target**: Binary classification (0 = No disease, 1 = Heart disease).

## Models Applied
- **Logistic Regression**: Chosen for its efficiency and interpretability in binary classification tasks.

## Key Results
- **Accuracy**: ~80.3%
- **ROC AUC**: High area under the curve, indicating strong model performance.
- **Top Predictors**: `thal` (thalassemia), `ca` (number of major vessels), and `cp` (chest pain type) were found to be some of the most influential features.

## How to Run
1. Ensure you have the required libraries installed: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `kagglehub`.
2. Run the `DevHub_ml_task_3.ipynb` notebook to see the full analysis, training, and evaluation process.
