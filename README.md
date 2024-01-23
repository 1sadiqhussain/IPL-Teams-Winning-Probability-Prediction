# IPL-Teams-Winning-Probability-Prediction
# 🏏 Cricket Match Outcome Predictor 🏆

Predict match winning probabilities and declare rain-affected winners using the Duckworth-Lewis method.

## Overview

This project implements machine learning models to predict the winning probabilities for both teams during the second inning of an IPL cricket match. Users can input details like current score, overs bowled, etc. and get probabilities from multiple regression algorithms. It also incorporates the Duckworth-Lewis calculations to account for rain delays and declare adjusted winners.

### Key Features

- 📈 Predictions from 5 regression models - Logistic, Random Forest, Decision Tree, XGBoost, Linear
- 🌧️ Duckworth-Lewis method implemented for rain-affected matches
- 🎛️ Customizable UI for interactive match simulations  
- ⚙️ Modular code for easy enhancements and model additions

## Usage

The Jupyter notebook contains the end-to-end implementation - data preparation, model training, evaluation, prediction and UI. To use it:

- Clone the repo and install dependencies
- Run the notebook cells to train models on the IPL dataset
- Use the UI cells to simulate match scenarios and get predictions
- Tweak the UI inputs and model choices for custom analyses 

## Data

The [IPL Dataset](https://www.kaggle.com/ramjidoolla/ipl-data-set) from Kaggle contains ball-by-ball data of all IPL matches from 2008 to 2019. The features used for prediction include:

- Batting and bowling teams
- Venue city 
- Runs scored 
- Overs and balls bowled
- Wickets lost
- Required run rate etc.

## Models

The following machine learning regression algorithms are implemented:

- Logistic Regression 
- Random Forest
- Decision Tree
- XGBoost 
- Linear Regression

Models are evaluated using R<sup>2</sup>, RMSE, accuracy, precision and learning curves. The best performing model is XGBoost with a test accuracy of 95.4%.

## Technologies

- ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
- ![Pandas](https://img.shields.io/badge/-Pandas-150458?logo=pandas&logoColor=white)
- ![NumPy](https://img.shields.io/badge/-NumPy-013243?logo=numpy&logoColor=white)
- ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?logo=scikit-learn&logoColor=white)
- ![Matplotlib](https://img.shields.io/badge/-Matplotlib-222222?logo=matplotlib&logoColor=white)
- ![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?logo=Jupyter&logoColor=white)

## Credits

- IPL ball-by-ball dataset from [Ramji Doolla](https://www.kaggle.com/ramjidoolla)
- DL method implementation guidance from research papers

Let me know if you would like any changes to this draft README! I'm happy to incorporate your feedback.
