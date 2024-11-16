# Health Care Prediction for Diabetic Patients - Case Study

## **Project Overview**
This project focuses on predicting the likelihood of diabetes in patients based on various health factors like glucose, blood pressure, BMI, etc. The goal is to build a classification model to predict the presence of diabetes using machine learning.

## **Context**
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

## **Dataset Description**
The dataset includes various medical predictor variables and one target variable, "Outcome." The predictor variables encompass essential health metrics, such as the number of pregnancies, plasma glucose concentration, diastolic blood pressure, triceps skinfold thickness, insulin levels, body mass index (BMI), diabetes pedigree function, and age.

### Predictor Values
1. Pregnancies:
Number of times pregnant

2. Glucose:
Plasma glucose concentration at 2 hours in an oral glucose tolerance test

3. BloodPressure:
Diastolic blood pressure (mm Hg)

4. SkinThickness:
Triceps skinfold thickness (mm)

5. Insulin:
2-Hour serum insulin (mu U/ml)

6. BMI:
Body mass index (weight in kg/(height in m)^2)

7. DiabetesPedigreeFunction:
Diabetes pedigree function
8. Age:
Age in years

### Target Variable
Outcome:
Class variable (0 or 1)
268 instances are labeled as 1 (indicating diabetes), while others are labeled as 0.

This dataset provides a valuable opportunity to develop a predictive model for diabetes based on demographic and health-related features

## Files Included
- `Health_Care_Prediction_for_Diabetic_Patients.ipynb`: The main Python script for data preprocessing, model training, and evaluation.
- `data/health care diabetes.csv`: The dataset used for training the model.
- `requirements.txt`: The list of Python libraries required to run the project.
