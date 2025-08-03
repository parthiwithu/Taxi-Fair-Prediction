# Taxi-Fair-Prediction
This project focuses on predicting taxi fare amounts using ML models. It includes thorough exploratory data analysis, preprocessing pipelines for handling numerical and categorical features, and implementation of multiple regression models including Linear Regression, Random Forest, Gradient Boosting, and XGBoost.evaluated using RMSE and R2 scores.
# Data Source
(https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- yellow_tripdata_2025-06
- [data_dictionary_trip_records_yellow.pdf](https://github.com/user-attachments/files/21566270/data_dictionary_trip_records_yellow.pdf)
# Taxi Fare Prediction using Machine Learning

This project aims to predict the fare amount for taxi rides based on various trip-related features using machine learning techniques. The dataset includes pickup/drop-off times, trip distance, passenger count, and more. A complete ML pipeline is built with preprocessing, model training, and evaluation.

## Project Overview

- Goal: Predict taxi fare amount using regression models.
- Dataset: NYC Taxi data with features like trip distance, time of day, day of the week, payment type, etc.
- Techniques Used:
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing with ColumnTransformer
- Model Training with multiple regressors
- Performance Evaluation using RMSE and R2
    
 ## Models Used

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

## Workflow

1. Data Cleaning and Feature Engineering
   - Removed outliers
   - Extracted date/time features
   - Created travel_time, pickup_hour, dayofweek, is_night, etc.

2. Exploratory Data Analysis (EDA)
   - Univariate, bivariate, and multivariate visualizations
   - - Correlation heatmaps
   - Boxplots and bar plots

3. Preprocessing
   - Numerical features scaled using StandardScaler
   - Categorical features encoded with OneHotEncoder
   - Combined using ColumnTransformer

4. Modeling
   - Pipelines built with preprocessing and model
   - Evaluation using RMSE and R2
