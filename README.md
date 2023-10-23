# Retail-Sales-Prediction--Regression-Project

Project Summary -

This project focuses on predicting retail sales for Rossmann Stores using historical data. The dataset includes information about the stores, competitors, types, holidays, customers, and sales transactions. The workflow involves data collection, cleaning, exploratory data analysis (EDA), feature engineering, and model implementation.

After data understanding, we cleaned and merged datasets, handled null values, and prepared features for visualization. EDA provided valuable insights for future machine learning model decisions.

Feature engineering and data preprocessing created new features like PromoDuration and CompetitionDuration while removing irrelevant features. Outliers were detected and treated, and categorical features were encoded numerically using One-Hot Encoding.

Data transformation techniques were applied to achieve normal distribution and scale uniformity. The dataset was split into training and testing sets. Several machine learning algorithms were used, including linear regression, decision trees, random forests, LGBM, and XGBoost.

Linear regression achieved 85.25% accuracy with an R2 score of 0.70.

Decision trees captured 90% of variance with 92.85% accuracy.

Random Forests reached 93.86% accuracy and reduced processing time.

XGBoost was the final model with 93.94% accuracy and 6.06% mean absolute percentage error.

The residuals' mean of 1.31 indicated normally distributed residuals, making XGBoost the optimal model for deployment.


Problem Statement - 

Rossmann, a large pharmacy chain with stores in 7 European countries, faces the challenge of accurately predicting daily sales for their over 3,000 stores. Store sales are influenced by numerous factors, including promotions, competition, holidays, seasons, and local conditions. Store managers are currently responsible for making these predictions, leading to variations in accuracy due to individual circumstances.

To address this issue, we have historical sales data for 1,115 Rossmann stores. The goal is to create a predictive model for the "Sales" column in the test dataset. It's important to note that some stores in the dataset were temporarily closed for refurbishment, which adds complexity to the forecasting task.

In simpler terms, the challenge is to build a model that can accurately predict the daily sales of Rossmann stores, taking into account various factors, and to do so consistently across all stores, even when some are temporarily closed for renovation. This can help Rossmann optimize their operations and resource allocation.
