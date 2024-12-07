House Price Prediction using Machine Learning
This project aims to predict house prices based on multiple features such as crime rate, room numbers, and distance from employment hubs. Various regression models were tested, including Linear Regression, Ridge, Lasso, Decision Trees, and Random Forest. The Gaussian Process Regressor delivered the best performance with a Mean Squared Error (MSE) of 14.23.

Data preprocessing and visualization were performed using Pandas, NumPy, and Seaborn, while Matplotlib was employed for presenting results.

Table of Contents
Introduction
Dataset
Technologies Used
Models Implemented
Best Model
Installation
Usage
Results
License
Introduction
House price prediction is a crucial task for real estate market analysis, helping stakeholders make informed decisions. This project focuses on building a regression model that predicts house prices using features like crime rate, air quality, and proximity to employment hubs. The project evaluates multiple machine learning models and identifies the most suitable approach for accurate predictions.

Dataset
The dataset contains 506 observations with the following features:

Feature	Description
price	Value of the house (target variable).
crime_rate	Crime rate in the neighborhood.
resid_area	Proportion of residential area in the town.
air_qual	Quality of air in the neighborhood.
room_num	Average number of rooms per house.
age	Age of the house (years).
dist1 to dist4	Distances from major employment hubs.
teachers	Number of teachers per 1000 population.
poor_prop	Proportion of poor population.
n_hos_beds	Number of hospital beds per 1000 population.
n_hot_rooms	Number of hotel rooms per 1000 population.
airport	Whether there is an airport in the town (Yes/No).
waterbody	Type of natural fresh water source (Lake/River/Both/None).
rainfall	Yearly average rainfall (cm).
parks	Proportion of land assigned as parks/green areas.
Technologies Used
Programming Language: Python
Libraries:
Data Manipulation: pandas, numpy
Machine Learning: scikit-learn, tensorflow
Visualization: matplotlib, seaborn
Models Implemented
The following regression models were implemented and tested:

Linear Regression
Ridge Regression
Lasso Regression
Decision Tree Regressor
Random Forest Regressor
Gaussian Process Regressor
K-Nearest Neighbors (KNN)
Support Vector Regressor (SVR)
Polynomial Regression
Neural Network Regression
Best Model
The Gaussian Process Regressor achieved the best performance with an MSE of 14.23, making it the most suitable model for this dataset.

