🚨 FBI Crime Forecaster Project

🔍 Project Overview:-

This project develops a predictive model to forecast monthly crime incidents using historical FBI crime data 📅. By leveraging data cleaning, feature engineering, and machine learning, the model produces reliable predictions to support crime analysis and prevention 🕵️‍♂️.

Both Random Forest and XGBoost were tested, with XGBoost delivering superior performance ⚡. Becaues those models are best for Time-Series Forecasting

🛠️ Tools & Technologies:

Tool	Purpose:-

🐍 Python	Main programming language

📊 Pandas	Data manipulation

🔢 NumPy	Numerical operations

🧠 Scikit-learn	Random Forest model

⚡ XGBoost	Boosting algorithm with better accuracy

📉 Matplotlib & Seaborn	Data visualization

📌 Project Workflow :

Data Cleaning & Preprocessing 🧹

Handle missing values

Date format conversion

Time-based feature creation

Exploratory Data Analysis (EDA) 📊

Monthly/yearly crime trends

Crime type distribution

Visual trend analysis

Feature Engineering 🔧

Lag features

Rolling averages

Time-based aggregations

Model Building & Training 🤖

Train/test split

Random Forest training

XGBoost training (better performance)

Hyperparameter tuning

Evaluation & Metrics 📈:-

Model	              MAE	   RMSE	   R² Score

Random Forest	     ~34.5	 ~62.0	 ~0.94

XGBoost ⚡        	33.82	 59.60	 0.94 ✅


📊 Key Insights:

Crime incidents show clear seasonal patterns 📆.

Lagging and rolling features significantly improve model accuracy ⚡.

XGBoost consistently outperformed Random Forest for this dataset 🏆.


💡 Future Enhancements

Add improvements in geospatial analysis for location-based forecasting 🌍.

Integrate real-time crime data for dynamic predictions ⏱️.

Deploy as a web-based dashboard 🌐.

📚 Learnings:

Understanding crime patterns can aid policy and policing decisions.

Feature engineering is key for improving model performance.

XGBoost’s boosting approach is highly effective for time-series crime prediction 📊.

Author:-

Umasankar Gudivada

September 2025


