# US Road Accidents: Severity Prediction and Analysis

This project analyzes the **US Road Accidents** dataset to predict accident severity, identify key factors contributing to accidents, and propose mitigation strategies. The Jupyter Notebook provided contains data exploration, preprocessing, model building, and evaluation.

## Table of Contents
- [Dataset Overview](#dataset-overview)
- [Project Objectives](#project-objectives)
- [Key Features](#key-features)
- [Project Workflow](#project-workflow)
- [Results](#results)


## Dataset Overview
The dataset contains information about over 1.5 million accidents that occurred across the US between 2016 and 2020. Key attributes include:
- **Date and Time**: The timestamp of the accident.
- **Location Details**: State, city, and specific coordinates.
- **Weather Conditions**: Visibility, temperature, humidity, and precipitation.
- **Road Conditions**: Surface type, traffic density, and lighting.
- **Severity**: A categorical variable ranging from 1 (low severity) to 4 (high severity).

## Project Objectives
1. **Predict Accident Severity**: Develop machine learning models to predict accident severity based on the available features.
2. **Analyze Key Factors**: Identify the most influential factors contributing to accident severity.
3. **Propose Mitigation Strategies**: Use insights to recommend strategies for reducing accidents.

## Key Features
- **Data Exploration**:
  - Descriptive statistics and visualizations.
  - Correlation analysis to understand relationships between variables.
- **Data Preprocessing**:
  - Handling missing values and outliers.
  - Feature engineering to extract new insights.
  - Data normalization and encoding for machine learning.
- **Modeling**:
  - Implementation of multiple machine learning models, including Logistic Regression, Random Forest, and Gradient Boosting.
  - Hyperparameter tuning for optimized performance.
- **Evaluation**:
  - Metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
- **Insights**:
  - Analysis of feature importance using SHAP values and other methods.
  - Temporal and spatial trends in accidents.
 
## Project Workflow
1. **Data Exploration**:
   - Conducted an in-depth analysis of the dataset to understand patterns and distributions.
   - Identified missing values, outliers, and anomalies.
2. **Data Cleaning and Preprocessing**:
   - Filled missing data using statistical and domain-specific methods.
   - Normalized and encoded categorical variables for machine learning compatibility.
3. **Feature Engineering**:
   - Created new features like `Day_of_Week`, `Is_Weekend`, and `Traffic_Density`.
   - Extracted temporal features such as `Hour_of_Day` and `Season`.
4. **Model Building**:
   - Trained and compared multiple machine learning models.
   - Used cross-validation to ensure generalizability.
   - Selected the best model based on evaluation metrics.
5. **Result Interpretation**:
   - Examined the importance of features contributing to severity prediction.
   - Developed visualizations to present findings clearly.
6. **Recommendations**:
   - Proposed actionable strategies to improve road safety based on data insights.

## Results
The project demonstrates:
- The effectiveness of machine learning models in predicting accident severity.
- Key factors such as weather, road conditions, and time of day significantly influencing accident severity.
- The importance of early identification of high-risk scenarios to mitigate accidents.
