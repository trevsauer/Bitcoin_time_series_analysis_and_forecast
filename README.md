# Bitcoin Price Time Series Analysis & Forecasting

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
Logistic regression achieved an accuracy rate of 95.98% for binary price change predictions.
Ensemble regression models with normal features demonstrated high accuracy in predicting cryptocurrency prices.
PCA-based models aimed to capture essential information while reducing dimensionality.

Discussion
Our analysis uncovered correlations between economic indicators and cryptocurrency prices, offering insights into trading strategies. While promising, further research is needed to comprehensively understand Bitcoin price dynamics.
Feel free to explore the code and results in the repository to gain deeper insights into Bitcoin trading and modeling techniques.
