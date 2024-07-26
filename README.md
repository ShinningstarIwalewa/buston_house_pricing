# Buston House Pricing 
This repository contains code and data for predicting house prices in Boston using a linear regression model. The project aims to provide insights into the real estate market, assisting various stakeholders like homebuyers, sellers, real estate agents, and investors in making informed decisions.

## Project Overview

The Boston House Price Prediction project is a machine learning project designed to predict house prices in Boston. The project involves:

- Data Exploration: Cleaning and analyzing the dataset to understand the relationships between features.
- Modeling: Implementing a linear regression model to predict house prices.
- Deployment: Deploying the model locally to provide real-time predictions.
  
Accurate house price predictions are crucial for various stakeholders in the real estate industry, enabling better decision-making and market understanding.

## Data Exploration
In the data exploration phase, the following steps were performed to ensure data quality and integrity:

- Identified and addressed missing data and ensured all data types were appropriate.
- Removed any duplicate entries to maintain data consistency.
- Analyzed the correlation between dependent and independent variables to identify significant relationships.
- Detected and handled outliers to prevent skewing the model's predictions.
  
This thorough data exploration ensured a solid foundation for building an accurate predictive model.

## Modeling
The project utilizes a simple linear regression model to predict house prices. The model was trained on the cleaned dataset and evaluated for accuracy. Here are the key steps involved in the modeling process:

- Divided the dataset into training and test sets.
- Used the training data to fit the linear regression model.
- Evaluated the model's performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

## Results
The linear regression model showed promising results, with an R-squared value of approximately 64% and an MAE of approximately 3. These results indicate the model's ability to predict house prices accurately based on the available data.

- R-Squared: Approximately 63.9% of the variance in the target variable is explained by the model. This suggests a moderately strong relationship between the predictors and the outcome. However, there is still room for imporovement

- MAE: The value of 3.3559 indicates that, on average, the predictions are off by about 3.36 units from the actual values. 
