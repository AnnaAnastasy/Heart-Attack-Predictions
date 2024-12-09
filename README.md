# Heart Attack Risk Analysis and Prediction

This project analyzes a dataset related to heart attack occurrences, performs exploratory data analysis (EDA), and builds predictive models to assess an individual’s risk of experiencing a heart attack. The objective is to provide actionable insights and predictive capabilities for healthcare professionals and organizations.

---

## Project Overview
Heart disease is a leading cause of mortality worldwide. This project aims to uncover patterns in heart attack risk factors through EDA and build machine learning models to predict the likelihood of a heart attack based on key features such as cholesterol levels, age, exercise-induced angina, and more.

## Dataset Description
The dataset used in this project contains records of patients and their associated health metrics. It includes variables such as cholesterol levels, resting blood pressure, maximum heart rate achieved, and exercise-induced angina.

Source: [Heart Attack Analysis & Prediction Dataset](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset)

## Features and Target Variable
- **Key Features:**
  - Age
  - Gender
  - Cholesterol Levels
  - Resting Blood Pressure
  - Maximum Heart Rate Achieved
  - Exercise-Induced Angina
  - Other relevant metrics
  
- **Target Variable:**
  - `Output` (1 = More likely to have a heart attack, 0 = Less likely)

## Methods and Tools
- **Programming Language:** Python
- **Libraries Used:** 
  - Data Analysis: `pandas`, `numpy`
  - Data Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`, `xgboost`, `tensorflow`
- **Jupyter Notebook**: The analysis and modeling are documented in an interactive notebook.

## Project Workflow
1. **Exploratory Data Analysis (EDA):**
   - Visualization of distributions and correlations among features.
   - Identification of key trends and outliers in the dataset.
   - Feature selection based on domain knowledge and statistical methods.

2. **Data Preprocessing:**
   - Handling missing values.
   - Standardizing and normalizing data where applicable.
   - Splitting the dataset into training and testing subsets.

3. **Modeling:**
   - Building machine learning models including Logistic Regression, Random Forest, and XGBoost.
   - Hyperparameter tuning to optimize performance.
   - Evaluating models using metrics such as Accuracy, Precision, Recall, and F1-Score.

4. **Results and Insights:**
   - Interpreting the feature importance.
   - Presenting actionable insights from EDA and model predictions.

## Key Results
- **Accuracy:** The chosen model achieved an accuracy of **0.87%**.
- **Key Insights:**
  - Features **chest pain type** and **maximum heart rate achieved** are highly correlated with heart attack risk.
  - Patients with **exercise-induced angina** have a significantly higher risk.


## Acknowledgments
- Thanks to the dataset contributors for making the data available.
