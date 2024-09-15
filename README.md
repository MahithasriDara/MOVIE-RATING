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

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/movie-rating-prediction.git
    cd movie-rating-prediction
    ```

2. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Download or place the dataset (e.g., `Movie dataset.csv`) in the repository's root directory.

4. Run the preprocessing and model training script:
    ```bash
    python train_models.py
    ```

## Usage

- The dataset needs to be preprocessed before training.
- You can switch between models by editing the script `train_models.py`.

### Example Commands

Run a linear regression model:
```bash
python train_models.py --model linear
