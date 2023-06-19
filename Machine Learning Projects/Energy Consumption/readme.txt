Energy Consumption Prediction

This project aims to predict energy consumption based on data collected from sensor. It involves analyzing the data, handling outliers,
performing feature engineering, and building ensemble regression learning models, as well as a Vector Auto Regression (VAR) model for
  multivariate time series analysis.

Project Overview:
- Data Analysis: Initial analysis to identify outliers in the data and removal of extreme outliers from the dataset.
- Feature Engineering: Exploration of linear relationships between independent and dependent variables, transformation and creation of
new features, and extraction of day, hour, and minute values from the datetime feature.
- Data Preprocessing: Standardization of the dataset using the StandardScaler to ensure all variables are on a similar scale.
- Ensemble Regression Learning Models: Construction of ensemble regression models including Random Forest Regression, Linear Regression,
Ridge Regression, Lasso Regression, and XGBoost Regressor. Evaluation of the models using Mean Absolute Error (MAE) and selection of 
XGBoost Regressor as the best-performing model.
- Vector Auto Regression (VAR) Model: Development of a VAR model to tackle the problem as a multivariate time series task. Training the 
VAR model on the dataset and evaluation of its performance.

Dependencies:
- Pandas
- NumPy
- scikit-learn
- XGBoost
- statsmodels
- math

Usage:
1. Install the necessary dependencies.
2. Preprocess the data.
3. Train and evaluate the ensemble regression learning models.
4. Build and assess the Vector Auto Regression (VAR) model.
5. Explore the results, compare model performances, and analyze the predictions made by the models.

Conclusion:
This project successfully predicts energy consumption based on Sensor data. The ensemble regression learning models and the Vector 
Auto Regression (VAR) model provide accurate predictions, with the XGBoost Regressor performing the best in terms of MAE. The project
offers insights into the relationship between independent variables and energy consumption and serves as a foundation for further 
improvements in energy consumption prediction.
