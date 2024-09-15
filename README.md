# Movie Rating Prediction

This project focuses on predicting movie ratings using various machine learning models, including Linear Regression, Decision Tree, Random Forest, and Support Vector Regression (SVR). The dataset contains features such as genre, director, and actors, which are preprocessed and encoded for model training.

## Project Overview

The goal of this project is to predict the movie rating using a variety of features like:
- Genre (one-hot encoded)
- Director and actors (average ratings and votes)
- User votes

We evaluate different models using metrics such as RMSE (Root Mean Squared Error) and R-squared.

## Features

1. **Movie Data Preprocessing**
    - Data cleaning (handling null values, removing outliers, etc.)
    - Feature engineering (calculating average ratings for directors, actors)
    - One-hot encoding for categorical data (genre)
    - Scaling numerical features

2. **Models Implemented**
    - Linear Regression
    - Lasso Regression (L1 Regularization)
    - Decision Tree Regressor
    - Random Forest Regressor
    - Support Vector Regression (SVR)

3. **Hyperparameter Tuning**
    - GridSearchCV is used for hyperparameter tuning of models like Random Forest and SVR.
   

### Instructions:
1. Replace `MahithaSriDara' with your GitHub username.
2. Customize the description to fit your exact project details, especially the model types and data sources.
3. If you have a different folder structure, update the "File Structure" section accordingly.
