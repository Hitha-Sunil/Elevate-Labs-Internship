# Project Overview

This HR Analytics project aims to identify key factors that influence employee attrition and visualize actionable insights through an interactive Power BI dashboard.
The goal is to help HR teams make informed, data-driven retention decisions by integrating predictive analytics with clear, visual storytelling.

# Dataset

Source: IBM HR Analytics Dataset

Records: 1,470 employees

Target Variable: Attrition (Yes/No)

# Key Steps

Data Preparation:
Cleaned and preprocessed the dataset in Python (handled missing values, encoded categorical variables, normalized numeric columns).

Exploratory Analysis:
Used Python (Matplotlib, Seaborn) to identify trends in attrition by age, department, gender, salary, and job satisfaction.

Model Building:
Implemented classification models such as Decision Tree, Logistic Regression, and Random Forest to predict attrition likelihood.

Dashboard Development (Power BI):
Created an interactive Power BI dashboard displaying:

Overall attrition rate

Attrition by department, gender, and job role

Salary distribution and job satisfaction levels

Key drivers of attrition based on model outputs and KPIs

Model Interpretation:
Applied SHAP values for feature-importance visualization and explainable AI insights.

# Key Insights

Overall attrition rate ≈ 16%

Higher attrition among employees with low job satisfaction and fewer promotions.

Sales and R&D departments show higher turnover.

Retained employees have higher average monthly income and greater work–life balance scores.

# Tools & Technologies

Python (Libraries): Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, SHAP

Visualization: Power BI (Interactive Dashboard)

Techniques: EDA, Feature Engineering, Classification Modeling, Explainable AI
