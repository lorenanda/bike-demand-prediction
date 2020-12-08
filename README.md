# Predicting Capital Bikeshare demands

This project was completed in week 3 of the Data Science Bootcamp at Spiced Academy.

## Description
I used the [Capital Bikeshare dataset](https://www.kaggle.com/c/bike-sharing-demand/) which contains daily records on the number of bikes rented as well as weather conditions. First, I ran an [exploratory data analysis](https://github.com/lorenanda/bike-demand-prediction/blob/main/project03_eda.ipynb) to detect patterns in the bike rental demand. Second, I used different [regression models](https://github.com/lorenanda/bike-demand-prediction/blob/main/project03_RandomForest.ipynb) to predict how many rental bikes are needed at a certain time, based on information about weather conditions and daily patterns:
- Linear Regression (R²: 0.66)
- Random Forest Regressor (RMSLE score: 0.47 / 0.49 in the Kaggle competition)
- Gradient Boosting Regressor (RMSLE: 0.09)
- Support Vector Regressor (RMSLE: 0.20)

![predictions](https://github.com/lorenanda/bike-demand-prediction/blob/main/predictions.svg)
