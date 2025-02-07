# Logistic-Regression-Model-for-Prediction-of-Heart-Disease

## Overview
This repository contains a statistical model for the binary classification task of predicting heart disease using clinical features from a public dataset. The model utilizes a Logistic Regression (LR) implementation to analyze patterns among clinical features as independent variables to predict the value of the target variable, representing the probability of heart disease.

## Clinical Features of the Dataset
- age; at the time of the study, measured in years
- sex; 1 represents female, 0 represents male
- trestbps; patient’s resting blood pressure, measured in mm Hg
- chol; patient’s cholesterol level in the blood, measured in mg/dL
- fbs; patient’s fasting blood sugar, measured in mg/dL
- restecg; patient’s resting electrocardiographic measurement (0 = normal, 1 = having ST-T wave abnormality)
- thalach; patient’s maximum heart rate achieved, measured in bpm
- exang; exercise induced angina (0 = no pain, 1 = pain)
- oldpeak; ST depression induced by exercise (‘ST’ refers to points on ECG plot)
- slope; slope of tangent line for peak exercise ST segment curve
- ca; number of major vessels colored by fluoroscopy
- thal; duration of exercise test in minutes
- target; class attribute (0 = healthy heart, 1 = heart defect)

## Results and Analysis
Based on the most recent cycle, the training data was associated with an accuracy score of 0.85124, while the testing/validation data was associated with an accuracy score of 0.81967. These metrics indicate the model's satisfactory performance in detecting heart disease in patients using logistic regression on a set number of clinical features. However, results of this study could have been improved in various ways, e.g. a larger and more varied dataset, a more advanced machine learning or deep learning algorithm with enhanced sensitivity to changes within data patterns, or an attempt to reduce bias within the dataset distribution.
