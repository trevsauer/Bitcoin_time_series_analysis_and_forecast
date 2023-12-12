# Bitcoin Price Time Series Analysis & Forecasting

![DALL·E 2023-12-11 17 46 07 - The artwork visualizes the concept of Bitcoin Price Time Series Analysis and Forecasting  It features a background of graphs and charts illustrating B](https://github.com/trevsauer/Bitcoin_time_series_analysis_and_forecast/assets/60379514/b2d4b0c1-935e-487f-80bc-afb6072203db)

Welcome to the Bitcoin Price Time Series Analysis project repository. This project focuses on leveraging time series analysis to gain insights into Bitcoin trading, particularly in the regions of Saudi Arabian Riyal (SAR) and the United States Dollar (USD).

Objective
Our goal is to understand seasonal patterns, develop price prediction models, and investigate historical arbitrage opportunities between these markets.

Datasets
We use the 'Digital_Currency.csv' dataset, spanning from May 7, 2018, to January 30, 2021, with ten columns and 1,000 rows of digital currency trading data. Additionally, seven supplementary datasets provide complementary information, including daily treasury rates, DOW Jones industrial average, daily Federal Funds rate, crude oil prices, inflation rates, and Economic Policy Uncertainty (EPU) Index for the U.S.

Modeling Overview
This project involves various modeling techniques:
Baseline Model: Establishing a simple benchmark for performance evaluation.
Logistic Regression: Predicting binary price changes with an accuracy rate of 95.98%.
Three Regressors with Original Features & PCA Features: Exploring dimensionality reduction using RandomForest, XGBoost, and GradientBoosting regressors with PCA-derived features.
Ensemble Regression Models with Original Features: Employing RandomForest, XGBoost, and GradientBoosting regressors with the original features.

Key Results
Logistic regression achieved an accuracy rate of 95.98% for binary price change predictions. When it comes to regression techniques for predicting cryptocurrency prices, ensemble models using the original features emerged as clear winners. The baseline model, employing the mean as a constant value, exhibited poor performance with elevated Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) values, coupled with near-zero R2 scores for both close_SAR and close_USD. In stark contrast, models trained on the original features, including RandomForest, XGBoost, GradientBoosting, and an ensemble model, consistently delivered exceptional results with R2 scores hovering around 0.997, signifying robust predictive power. Among these, the ensemble model outshone the rest, consistently yielding the lowest MAE and RMSE values for both target variables. This underscores the effectiveness of combining decision tree-based algorithms (RandomForest, XGBoost, GradientBoosting) with an ensemble approach. In conclusion, for regression techniques, the ensemble model and models utilizing original features proved to be the most adept at accurately forecasting both close_SAR and close_USD, eclipsing the baseline model and PCA-transformed features. These models are ideally suited for this dataset and task, demonstrating their superior performance and capability to capture underlying data patterns.

Discussion
Our analysis uncovered correlations between economic indicators and cryptocurrency prices, offering insights into trading strategies. While promising, further research is needed to comprehensively understand Bitcoin price dynamics.
Feel free to explore the code and results in the repository to gain deeper insights into Bitcoin trading and modeling techniques.
