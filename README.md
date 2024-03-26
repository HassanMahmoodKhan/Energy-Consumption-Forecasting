# Energy-Consumption-Forecasting

This repository contains code and resources for performing time series forecasting to predict hourly energy consumption across multiple US states. The models implemented here aim to provide accurate forecasts to support energy demand planning and resource allocation.

## Table of Contents
- Introduction
- Dataset
- Installation
- Usage
- Models
- Evaluation
- License

## Introduction
In this project, I leverage time series forecasting techniques to predict hourly energy consumption for various states in the US. By analyzing historical energy consumption data and other relevant factors, my goal is to develop accurate forecasting models that can assist energy providers and policymakers in making informed decisions regarding energy production and distribution.

## Dataset
The dataset used for this project consists of hourly energy consumption data for multiple states for a regional transmission organization (RTO) in the United States. It is part of the Eastern Interconnection grid operating an electric transmission system serving all or parts of Delaware, Illinois, Indiana, Kentucky, Maryland, Michigan, New Jersey, North Carolina, Ohio, Pennsylvania, Tennessee, Virginia, West Virginia, and the District of Columbia.

The hourly power consumption data comes from PJM's website and are in megawatts (MW). It can be found at this [link](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption?resource=download&select=FE_hourly.csv).

## Installation
To set up the project environment, follow these steps:
1- Clone the reposository:
```
git clone https://github.com/HassanMahmoodKhan/Energy-Consumption-Forecasting.git
```

2- Install the required dependencies:
```
pip install -r requirements.txt
```

## Usage
To use the forecasting model implemented in this repository, simply run the `.ipynb` file. The Colaboratory file employs the following steps:

- Preprocess the dataset to prepare it for model training.
- Perform exploratory data analysis to view patterns and general trend.
- Train the forecasting model using the preprocessed data.
- Evaluate the performance of the trained model using appropriate metrics.
- Use the trained models to generate forecasts for future energy consumption.

## Models
The repository includes implementation of the `XGBoost Regressor` model, employing numerous `Decision Tree` models to perform forecasting/regression.

## Evaluation
I evaluate the performance of the forecasting models using metrics such as Mean Squared Error (MSE) and Root Mean Squared Error (RMSE). Additionally, I provide visualizations to compare the actual and predicted energy consumption values across multiple dimensions i.e., hourly, weekly, monthly, etc. Please refer to the assets folder for the visulaizations.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
