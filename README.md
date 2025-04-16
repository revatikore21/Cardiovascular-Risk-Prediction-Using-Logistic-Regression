# Cardiovascular-Risk-Prediction-Using-Logistic-Regression
## Overview
This project aims to develop a Logistic Regression model to estimate the likelihood of developing Coronary Heart Disease (CHD) over a 10-year period. The analysis is based on a dataset with 4,328 patient records. The target variable is binary:

1: Indicates elevated risk of CHD

0: Indicates low risk of CHD

## Dataset Description
The dataset includes various clinical and demographic variables that influence the risk of CHD. Key features are:

Sex: Gender of the individual (Categorical)

Age: Patient’s age in years (Continuous)

Current Smoker: Whether the individual is currently smoking (Categorical)

Cigs Per Day: Average number of cigarettes smoked daily (Continuous)

BP Meds: Whether the patient is on medication for blood pressure (Categorical)

Prevalent Stroke: History of stroke (Categorical)

Prevalent Hyp: History of hypertension (Categorical)

Diabetes: Presence of diabetes (Categorical)

Total Cholesterol (Tot Chol): Measured cholesterol level (Continuous)

Systolic BP (Sys BP): Systolic blood pressure (Continuous)

Diastolic BP (Dia BP): Diastolic blood pressure (Continuous)

BMI: Body Mass Index (Continuous)

Heart Rate: Pulse rate (Treated as continuous)

Glucose: Blood glucose level (Continuous)

## Model Development
A Logistic Regression model was developed and evaluated to predict the CHD risk. Initial training of the model yielded an accuracy of 84%, which reflects strong performance. However, due to possible class imbalance, additional evaluation metrics were considered.

## Model Optimization
To enhance model performance, GridSearchCV was employed for hyperparameter tuning. This optimization improved the model’s accuracy from 84% to 85%.

## Workflow Summary
Data loading

Data preprocessing (missing value treatment, encoding, feature scaling)

Model training using Logistic Regression

Performance evaluation using metrics: accuracy, precision, recall, and ROC-AUC

Model tuning with GridSearchCV

## Conclusion
This model demonstrates a reliable baseline method for forecasting 10-year CHD risk. With post-tuning accuracy of 85%, it serves as a strong starting point for further cardiovascular risk analysis and preventive healthcare strategies.

