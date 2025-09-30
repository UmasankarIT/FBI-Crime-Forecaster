FBI Crime Forecaster Project

Project Overview:-

The FBI Crime Forecaster Project is a machine learning initiative designed to forecast monthly crime incidents using historical FBI crime data.
The project demonstrates a complete workflow: data cleaning, feature engineering, model building, and evaluation, producing an accurate system for crime trend forecasting.

Objectives:-

Predict monthly crime counts using historical crime data.

Explore temporal patterns and seasonality in crime trends.

Compare different machine learning models for forecasting.

Evaluate models using meaningful metrics such as MAE, RMSE, and R² score.

Key Features:-

Time-series analysis of crime incidents.

Lag feature engineering to capture trends and seasonality.

Modeling with Random Forest and XGBoost regressors.

Comprehensive model evaluation.

Visualizations of crime trends and predictions.

Dataset:-

The dataset contains FBI crime incident records, including:

Date and time of incident

Crime type

Location

Additional descriptive features

Note: Data cleaning and preprocessing have been applied to ensure accuracy and consistency before modeling.

Tools & Libraries

Python

Pandas

NumPy

Scikit-learn

XGBoost

Matplotlib / Seaborn

Jupyter Notebook

Workflow:-

Data Preparation: Converting dates, extracting year and month, and aggregating monthly crime counts.

Feature Engineering: Creating lag features to capture historical trends and seasonality.

Train-Test Split: Using data before 2011 for training and data from 2011 for testing.

Model Building: Training Random Forest and XGBoost regressors.

Model Evaluation: Assessing performance with MAE, RMSE, and R² metrics.

Results :-

Model	MAE	RMSE	R² Score
Random Forest	34.53	62.00	0.94
XGBoost	35.82	59.60	0.94

Best model: XGBoost, achieving MAE ≈ 35.82 and R² ≈ 0.94 — showing excellent accuracy for monthly crime prediction.

Insights :-

Crime incidents exhibit strong seasonal patterns.

Lag features significantly improve forecasting accuracy.

XGBoost slightly outperforms Random Forest.

Further performance gains possible with additional features such as weather, demographics, and economic indicators.

How to Run:-

Clone the repository.

Install dependencies.

Run the model training script.


Future Improvements :-

Add seasonality and holiday-based features.

Integrate external data sources (weather, census, economic indicators).

Explore advanced time-series models such as Prophet or LSTM.

Build crime type–specific prediction models.

Develop a web-based dashboard or API for real-time crime prediction.

About:-

This project demonstrates a full data science pipeline from data preparation to model evaluation for time-series prediction.
It is ideal for showcasing skills in machine learning, time-series forecasting, and crime analytics.
