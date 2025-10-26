# Project Overview

This project focuses on predicting whether patients will attend or miss their scheduled medical appointments. The goal is to assist healthcare providers in optimizing appointment scheduling, reducing resource wastage, and improving patient care efficiency.

# Dataset

Source: Public healthcare appointment dataset

Records: 110,527 appointments

Target Variable: no_show (Yes = 1, No = 0)

# Key Steps

Data Cleaning: Handled missing values, corrected column names, removed invalid ages, and standardized categorical data.

Feature Engineering: Added new columns like wait_days, appointment_weekday, and is_weekend.

Preprocessing: Applied one-hot encoding for categorical features and standard scaling for numerical data.

Modeling: Used a Decision Tree Classifier with GridSearchCV to optimize parameters.

Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

# Results

*Accuracy: 57.45%*

*Recall: 83.62% (indicating effective identification of no-shows)*

*ROC-AUC: 0.72*

Key Insights:

Shorter waiting periods reduce no-show rates.

SMS reminders improve attendance.

Weekends and certain weekdays show higher no-show rates.

# Tools & Libraries

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
