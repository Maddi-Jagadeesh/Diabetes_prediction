Diabetes Prediction Model using Linear SVM

Overview

This project is a machine learning model that predicts whether a person has diabetes based on medical data. 
The model is built using Support Vector Machine (SVM) with a linear kernel and trained on the Pima Indians Diabetes Dataset.

Dataset

The dataset used is the Pima Indians Diabetes Dataset, which contains 768 samples with 8 medical predictor variables and
a target variable indicating the presence of diabetes (1 for diabetic, 0 for non-diabetic).

Features:

Pregnancies - Number of times pregnant
Glucose - Plasma glucose concentration
BloodPressure - Diastolic blood pressure (mm Hg)
SkinThickness - Triceps skin fold thickness (mm)
Insulin - 2-Hour serum insulin (mu U/ml)
BMI - Body mass index (weight in kg/(height in m)^2)
DiabetesPedigreeFunction - Diabetes pedigree function
Age - Age in years
Outcome - Class variable (0 = Non-diabetic, 1 = Diabetic)

Model and Approach

Data Preprocessing: Handling missing values, feature scaling using StandardScaler.
Model Selection: Linear Support Vector Machine (SVM) is used for classification.

Training and Evaluation:

Train-test split (80% training, 20% testing)
Performance evaluation using Accuracy


Author: Maddi Jagadeesh

