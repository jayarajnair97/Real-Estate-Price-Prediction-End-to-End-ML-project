# Real-Estate-Price-Prediction-End-to-End-ML-project
## Real Estate Price Prediction using Machine Learning
## Introduction
Real estate price forecasting is crucial for various stakeholders, including developers, homeowners, and investors. Accurate price predictions aid in risk management, investment planning, and informed decision-making. This project aims to create a prediction model that can reliably estimate the cost of a home per unit area based on several property characteristics.

## Dataset Description
The dataset contains 414 records of real estate transactions with the following features:
Transaction date: Date of the property transaction.
House age: Age of the property in years.
Distance to the nearest MRT station: Proximity to the nearest Mass Rapid Transit station in meters.
Number of convenience stores: Count of convenience stores in the vicinity.
Latitude and Longitude: Geographical coordinates of the property.
House price of unit area: Target variable representing the house price per unit area.
Objective
The main goal is to construct a machine learning model that accurately predicts the cost of a home per unit area based on various property characteristics.

## Project Procedure
Data Preprocessing: Selecting relevant features and target variable, and splitting the dataset into training and testing sets.
Model Training: Training a Linear Regression model using the training data.
Dash App Development:
Designing the app layout using Dash's HTML and Core Components.
Writing callback functions to specify the application's interactivity and execute the model prediction.
Loading the trained model into the app for predictions.

## Tools and Techniques
Libraries Used:
pandas
scikit-learn
Dash
Machine Learning Algorithm: Linear Regression

## Key Findings
The machine learning model developed for real estate price prediction achieved an accuracy of [insert accuracy score] on the test dataset.
The most significant predictors of house price per unit area were found to be distance to the nearest MRT station, number of convenience stores, latitude, and longitude.
Files Included
Real_Estate.csv: Dataset containing real estate transaction records.
Real_Estate_Price_Prediction_App.py: Python script containing the Dash application code for real estate price prediction.

## Instructions to Run the Application
Ensure that all the required libraries are installed.
Run the Python script Real_Estate_Price_Prediction_App.py.
Access the application on your web browser.

## How to Use the Application
Enter the required property details, including distance to the nearest MRT station, number of convenience stores, latitude, and longitude.
Click on the "Predict Price" button to get the predicted house price per unit area.

By accurately predicting real estate prices, this model provides valuable insights for various stakeholders, aiding them in making informed decisions and mitigating risks.
