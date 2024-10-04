# Machine Learning Regression Taxi Orders

Training and Testing models on time series data to predict taxi orders.

This notebook works with training three different regression models (LinearRegression, XGBoost, and LightGBM).

Performs an EDA in a time series data, create a function to perform feature engineering, and do a manual train/test/validation split.

Uses Optuna for hyperparameter tuning to reduce the RMSE of the models and choose the best one.