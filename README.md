# Car Price Prediction Project

This repository contains a project for predicting car prices using various regression models. The dataset is provided by Kaggle and includes multiple features of cars that are used to train the models.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The goal of this project is to build and evaluate different regression models to predict the prices of cars based on various features. The models include:

- Ridge Regression
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- K-Neighbors Regressor
- Support Vector Regressor
- XGBoost Regressor
- Gradient Boosting Regressor

The best model based on Root Mean Squared Error (RMSE) is selected and its parameters are optimized using GridSearchCV.

## Dataset

The dataset is available in the `car_price_prediction.csv` file from the Kaggle competition. It includes the following columns:

- `ID`: Unique identifier for each car
- `Price`: Price of the car (target variable)
- `Levy`: Levy on the car
- `Manufacturer`: Manufacturer of the car
- `Model`: Model of the car
- `Prod. year`: Production year of the car
- `Category`: Category of the car
- `Leather interior`: Whether the car has a leather interior
- `Fuel type`: Type of fuel used by the car
- `Engine volume`: Volume of the engine
- `Mileage`: Mileage of the car
- `Cylinders`: Number of cylinders in the engine
- `Gear box type`: Type of gear box
- `Drive wheels`: Type of drive wheels
- `Doors`: Number of doors
- `Wheel`: Type of wheel
- `Color`: Color of the car
- `Airbags`: Number of airbags

## Installation

To run this project, you need to have Python 3 and the following libraries installed:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- xgboost

