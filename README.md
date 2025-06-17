# Household_power_consumption

This project aims to forecast household energy consumption using machine learning models. 
The dataset consists of historical power usage data, and the project follows a structured pipeline
including preprocessing, outlier removal, skewness correction, feature engineering, model training,
hyperparameter tuning, and evaluation.

# Preprocessing Summary

- Handled missing values with forward-fill.
- Removed outliers using IQR method.
- Applied log transformation to reduce skewness.
- Extracted time-based features: hour, day, month, weekday, weekend.
- Computed rolling average for 1-hour intervals.
- Scaled features using StandardScaler.

# Training Models

Linear Regression 

Random Forest 

Gradient Boosting 

Neural Network 

# Model Evaluation Metrics

RMSE

MAE

R2 Score
