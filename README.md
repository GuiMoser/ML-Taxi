# Machine Learning Regression Taxi Orders

## Project Description
Training and Testing models on time series data to predict taxi orders.

This notebook works with training three different regression models (LinearRegression, XGBoost, and LightGBM).

Performs an EDA in a time series data, create a function to perform feature engineering, and do a manual train/test/validation split.

Uses Optuna for hyperparameter tuning to reduce the RMSE of the models and choose the best one.

## Objectives
- Perform exploratory data analysis.
- Select the best features to split between training, validation and testing.
- Train and tune three different regression models (LinearRegression, XGBoost, and LightGBM).
- Compare the performance of the models and choose the best one.

## Tools and Libs used
- Python: Main language used for analysis.
- Pandas: Library for data manipulation and analysis.
- NumPy: Library for numerical operations.
- Matplotlib and Seaborn: Libraries for data visualization.
- Scikit-learn: Library for machine learning.
- Optuna: Library for hyperparameter tuning.
- LightGBM e XGBoost: Libs for gradient boosting.

## Methodology
#### EDA
- Import libraries.
- Load the dataframes.
- Perform exploratory data analysis using summary statistics and data visualization.
#### Preprocessing
- Identify and treat missing values.
- Identify and treat outliers.
- Select the best features to split between training, validation and testing.
#### Model Training
- Train three different regression models (LinearRegression, XGBoost, and LightGBM).
- Perform hyperparameter tuning using GridSearchCV.
#### Model Evaluation
- Compare the performance of the three models and select the best one.

## Learnings
- Data analysis: Interpreting and extracting valuable insights from large volumes of data.
- Data cleaning: Identifying and correcting missing, duplicate, and anomalous values.
- Creating graphics: Using matplotlib and seaborn to visualize data in an intuitive and informative way.
- Data preprocessing: Preparing Data for analysis, including cleaning and treat the data.
- Use of libraries and tools: Practical application of various libraries and tools from the Python ecosystem, such as Pandas, Numpy, Sklearn, Matplotlib and Seaborn.
- Data visualization: Creating very detailed graphs and other types of visualizations to identify patterns and trends.
- Data-driven decision making: Using insights derived from data analysis to guide strategic decisions.
- Regression Models: Train and evaluate regression models.
- Model comparison: Compare models based on different metrics
- Feature selection: Selecting the best features to split between training, validation and testing.
- Hyperparameter tuning: Using Optuna to find the best hyperparameters for the models.