# Data-Science---Forecasting
Airlines Passengers Forecasting
This project focuses on forecasting airline passenger data using various time series forecasting models. Different models are implemented and evaluated, and this document provides explanations for each model's approach, the number of dummy variables created, and the Root Mean Squared Error (RMSE) value for each model. Finally, a recommendation is made regarding the model to be used for forecasting.

Table of Contents
Project Description
Getting Started
Dataset
Exploratory Data Analysis
Time Series Decomposition
Forecasting Models
Model Evaluation
Conclusion
Project Description
The project's primary goal is to forecast airline passenger data. To achieve this, different time series forecasting models are implemented and evaluated. The models are assessed based on their RMSE values, and the model with the lowest RMSE is recommended for forecasting.

Problem Statement
The objective is to select the best forecasting model for airline passenger data. Various models are implemented, and their performance is evaluated to determine which model provides the most accurate forecasts.

Key Steps and Components
Data Collection: The project begins with the import of an airline passenger dataset from an Excel file.

Exploratory Data Analysis (EDA): EDA is conducted to understand the dataset, including data shape, statistics, and visualization to identify trends and patterns.

Time Series Decomposition: Time series decomposition is performed to identify seasonality and trend components in the data.

Forecasting Models: Various forecasting models are implemented, including Simple Moving Average, Simple Exponential Smoothing, Holt's Method, Holt's Exponential Smoothing (Additive and Multiplicative), and ARIMA.

Model Evaluation: The RMSE values are calculated for each forecasting model to assess their accuracy.

Conclusion: Based on RMSE values, the best forecasting model is recommended for future use.

Getting Started
To use or replicate this project:

Ensure you have Python installed on your system.

Install the required libraries using pip install pandas numpy matplotlib statsmodels scikit-learn.

Clone the project repository.

Run the provided Jupyter Notebook or Python script to explore the dataset, build and evaluate forecasting models.

Dataset
The dataset used in this project contains airline passenger data, with a focus on time-based information.

Conclusion
In this project, various time series forecasting models were implemented and evaluated to forecast airline passenger data. The RMSE values for each model were calculated to assess their accuracy. After comparing the RMSE values, the Holt's Exponential Smoothing model with multiplicative seasonality and additive trend was selected as the best model for forecasting airline passenger data.

This project serves as a reference for time series forecasting tasks and provides insights into the selection of an appropriate forecasting model based on RMSE values.

COCA-COLA DATASET
CocaCola Prices Forecasting
This project aims to forecast CocaCola prices using various time series forecasting models. The code includes explanations for each model's approach, the number of dummy variables created, and the Root Mean Squared Error (RMSE) value for each model. Ultimately, a recommendation is made regarding the model to use for forecasting.

Table of Contents
Project Description
Getting Started
Dataset
Exploratory Data Analysis
Feature Engineering
Time Series Analysis
Forecasting Models
Model Evaluation
Conclusion
Project Description
The project focuses on forecasting CocaCola prices using time series forecasting models. Different models are implemented and evaluated, and the RMSE values are calculated to assess their accuracy. The model with the lowest RMSE is recommended for forecasting.

Problem Statement
The objective is to determine the best forecasting model for CocaCola prices. Multiple forecasting models are implemented and evaluated to select the most accurate model.

Key Steps and Components
Data Collection: The project begins with the import of a CocaCola prices dataset from an Excel file.

Exploratory Data Analysis (EDA): EDA is conducted to understand the dataset, including data shape, statistics, and visualization to identify trends and patterns.

Feature Engineering: Feature engineering is applied to modify the dataset and make it suitable for time series analysis.

Time Series Analysis: Time series analysis is performed, including decomposition to identify seasonality and trend components.

Forecasting Models: Various forecasting models are implemented, including Simple Moving Average, Simple Exponential Smoothing, Holt's Method, Holt's Exponential Smoothing (Additive and Multiplicative), and ARIMA.

Model Evaluation: The RMSE values are calculated for each forecasting model to assess their accuracy.

Conclusion: Based on RMSE values, the best forecasting model is recommended for future use.

Getting Started
To use or replicate this project:

Ensure you have Python installed on your system.

Install the required libraries using pip install pandas numpy matplotlib statsmodels scikit-learn.

Clone the project repository.

Run the provided Jupyter Notebook or Python script to explore the dataset, build and evaluate forecasting models.

Dataset
The dataset used in this project contains CocaCola prices, focusing on quarterly data.

Conclusion
In this project, various time series forecasting models were implemented and evaluated to forecast CocaCola prices. The RMSE values for each model were calculated to assess their accuracy. After comparing the RMSE values, Holt's model was selected as the best forecasting model for CocaCola prices.

This project serves as a reference for time series forecasting tasks and provides insights into the selection of an appropriate forecasting model based on RMSE values.
