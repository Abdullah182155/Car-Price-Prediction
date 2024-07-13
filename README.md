Car Price Prediction Challenge
Overview
This repository contains code for predicting car prices based on various features using machine learning models.

Dataset
The dataset used (car_price_prediction.csv) includes the following columns:

Price: Target variable (car price)
Levy: Tax paid on the car
Manufacturer: Car manufacturer
Prod. year: Year of production
Category: Car category (e.g., Sedan, Jeep)
Fuel type: Type of fuel used
Engine volume: Volume of the car engine
Mileage: Distance traveled by the car
Cylinders: Number of cylinders in the engine
Gear box type: Type of gearbox (e.g., Automatic, Manual)
Drive wheels: Type of drive wheels (e.g., Front, 4x4)
Doors: Number of doors
Wheel: Steering wheel position (Left wheel, Right-hand drive)
Color: Car color
Airbags: Number of airbags in the car
Data Preprocessing
Removed unnecessary columns (ID, Model)
Dropped duplicate entries
Encoded categorical variables using LabelEncoder
Scaled numerical features using MinMaxScaler
Exploratory Data Analysis
Created a correlation heatmap to understand feature relationships
Models Evaluated
Ridge Regression
Linear Regression
Decision Tree Regression
Random Forest Regression
K-Nearest Neighbors Regression
Support Vector Regression (SVR)
XGBoost Regressor
Gradient Boosting Regressor
Best Model
Based on Root Mean Squared Error (RMSE), the XGBoost Regressor with the following parameters performed best:

n_estimators: 10
loss: 'ls'
Usage
Clone the repository: git clone https://github.com/your_username/car-price-prediction.git
Install dependencies: pip install -r requirements.txt
Run the script: python car_price_prediction.py
Contributors
Abdullah Emara
License
This project is licensed under the MIT License - see the LICENSE file for details.
