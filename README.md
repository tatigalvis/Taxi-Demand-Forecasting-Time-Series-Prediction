📌 Project Overview

This project focuses on forecasting the number of taxi orders for the next hour using historical airport demand data. The objective is to help optimize driver allocation during peak hours by accurately predicting short-term demand.

🎯 Objectives

Predict hourly taxi demand using time series modeling

Achieve an RMSE ≤ 48 on the test dataset

Improve operational efficiency through demand forecasting

📊 Dataset

The dataset contains time-indexed data of taxi orders:

datetime — timestamp of each observation

num_orders — number of taxi orders

⚙️ Data Preprocessing

Resampled data to hourly frequency

Sorted and indexed data by datetime

Created time-based features (hour, day, lag features)

Generated rolling mean features for trend analysis

Split data into training and test sets (90% / 10%)

🤖 Models Used

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting (optional)

📈 Evaluation Metric

RMSE (Root Mean Squared Error)

🔍 Key Steps

Data resampling and preprocessing

Feature engineering (lags and rolling means)

Model training and hyperparameter tuning

Model evaluation using RMSE

Selection of best-performing model

🚀 Results

Successfully achieved RMSE below the required threshold (≤ 48)

Tree-based models outperformed baseline models

Lag features significantly improved model performance

Final model effectively captured temporal patterns in demand

🧠 Key Learnings

Importance of feature engineering in time series problems

Role of lag and rolling features in improving predictions

Handling time-based data splits (no random shuffle)

Model selection based on forecasting performance

🛠️ Tools & Technologies

Python

Pandas

NumPy

Scikit-learn

Matplotlib

📌 Conclusion

This project demonstrates how machine learning can be applied to time series forecasting to support real-time operational decisions. Accurate demand prediction can help optimize driver allocation and improve service efficiency.
