# EPL-Match-Outcome-Prediction
This project predicts the outcome of English Premier League (EPL) matches using machine learning models. The outcome is classified into three categories:
- **Home Win (H)**
- **Draw (D)**
- **Away Win (A)**

## What’s Inside:
- **Data Preparation**: Unnecessary and highly redundant columns (e.g., `Date`, `HomeTeam`, `AwayTeam`, `FTHG`, `FTAG`) were dropped to simplify the dataset.
- **Feature Encoding**: The target variable (`FTR`) was encoded into numerical values for model training.
- **Model Comparison**: Three machine learning models—**Logistic Regression (LR)**, **Random Forest (RF)**, and **XGBoost (XGB)**—were trained and evaluated to predict match outcomes.
- **Visuals**: Visualizations include distribution plots for categorical features and correlation heatmaps to understand the data.

## Tools Used:
- **Python** (pandas, numpy, scikit-learn, xgboost)
- **Matplotlib** and **Seaborn** for data visualization
- **Jupyter Notebooks** for interactive analysis
- **GitHub** for managing and sharing the project

## Key Insights:
- **Logistic Regression** achieved the highest accuracy (64.91%) among the three models.
- **Random Forest** performed slightly worse with an accuracy of 64.04%.
- **XGBoost** achieved an accuracy of 60.31%, indicating room for improvement with hyperparameter tuning.
