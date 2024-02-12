# Randomized-Search

House Price Prediction Project
This project aims to create a model using various machine learning algorithms to predict house prices.

Data Acquisition
The dataset used for house price prediction can be downloaded from here.

Data Preprocessing
The following steps were carried out during the data preprocessing stage:

One Hot Encoding: Conversion of categorical features.
Removal of Outliers: Detection and removal of outliers.

Modeling
The algorithms used for house price prediction are as follows:

XGBRegressor with RandomizedSearchCV: XGBoost is an optimized implementation of the gradient boosting algorithm. RandomizedSearchCV performs a random search to determine the best combination of hyperparameters for the model.

Random Forest Regressor with RandomizedSearchCV: Random Forest is an ensemble algorithm that consists of many decision trees. RandomizedSearchCV finds the best parameter combination by randomly selecting them.

Catboost with RandomizedSearchCV: CatBoost is a gradient boosting algorithm that automatically handles categorical variables. RandomizedSearchCV performs a random search to determine the best combination of hyperparameters for the model.

Support Vector Regression with RandomizedSearchCV: Support Vector Regression separates data points with a line (or plane, or multiple hyperplanes in higher dimensions) instead of classifying them. RandomizedSearchCV performs a random search to determine the best combination of hyperparameters for the model.

GradientBoostingRegressor with RandomizedSearchCV: Gradient Boosting is an ensemble algorithm where many weak learners combine to create a strong predictor. RandomizedSearchCV performs a random search to determine the best combination of hyperparameters for the model.

KNeighborsRegressor with RandomizedSearchCV: K-Nearest Neighbors uses the nearest data points to predict a point in the dataset. RandomizedSearchCV performs a random search to determine the best combination of hyperparameters for the model.

Bagging Regressor: Bagging is an ensemble algorithm where the same algorithm is run on different subsets of the dataset, and the results are combined. Bagging Regressor applies this method to regression problems.

Getting Started
To run the project on your local machine, follow the steps below:

Clone this project:
git clone https://github.com/zeynepyarentas/Randomized-Search-House-Price-Prediction

Install the necessary dependencies:
pip install -r requirements.txt

