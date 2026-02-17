# Healthcare Readmission Analytics and Prediction System

## Overview
This project presents an end-to-end healthcare analytics pipeline designed to analyze hospital patient records and predict the likelihood of **30-day hospital readmission** using machine learning techniques. The system performs data preprocessing, exploratory data analysis (EDA), feature engineering, predictive modeling, and performance evaluation to identify key clinical and demographic factors influencing readmissions.

## Objectives
- Analyze healthcare patient datasets to discover patterns related to readmission.
- Identify important features affecting patient readmission risk.
- Build machine learning models to predict 30-day readmission probability.
- Provide actionable insights for improving hospital decision-making and patient care.

## Dataset
The project uses a healthcare dataset containing patient admission records, demographic details, diagnosis information, treatment data, and readmission outcomes.

## Technologies Used
- Python
- Pandas, NumPy – Data processing
- Matplotlib, Seaborn – Data visualization
- Scikit-learn – Machine learning modeling
- Jupyter Notebook – Development environment

## Methodology
1. Data cleaning and preprocessing  
2. Missing value handling and feature engineering  
3. Exploratory Data Analysis (EDA)  
4. Model building (Logistic Regression, Random Forest)  
5. Model evaluation using Accuracy, Precision, Recall, F1-Score, and ROC-AUC  

## Results
The developed models successfully predict patient readmission risk and highlight significant contributing factors such as inpatient visits, emergency visits, number of diagnoses, and patient age.

## Project Structure
├── data/                # Dataset files
├── notebooks/           # Jupyter notebooks
├── visualizations/      # Generated charts and plots
├── models/              # Trained model outputs
└── README.md
