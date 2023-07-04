# Startup_Success-Prediction
# Multiple Linear Regression for Startup Success Prediction

This project implements multiple linear regression to predict the success of startups based on various features. It utilizes the scikit-learn library in Python for building and evaluating the regression model.

## Dataset

The dataset used in this project is stored in the file `50_Startups.csv`. It contains information about 50 startups, including their R&D spending, administration spending, marketing spending, state, and profit. The dataset is divided into input features (X) and the target variable (y) for training the regression model.

## Requirements

To run this project, you need the following dependencies:

- Python 3.x
- numpy
- pandas
- matplotlib
- scikit-learn
- statsmodels
##Description
Project aims to predict the success of startups based on various features using multiple linear regression. It leverages the scikit-learn library in Python to build and evaluate the regression model.

The project utilizes a dataset called 50_Startups.csv, which contains information about 50 startups, including their R&D spending, administration spending, marketing spending, state, and profit. By analyzing this dataset and implementing multiple linear regression, the project aims to identify the key factors that contribute to startup success.

The regression model is trained on a subset of the data, and its performance is evaluated on a test set. To enhance the model, the project implements backward elimination, an iterative feature selection technique that eliminates non-significant features from the model based on p-values. This refinement process helps identify the most influential features for predicting startup success.

