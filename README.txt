NBA Player Analysis with MLP Regressor

Overview

This project analyzes NBA player statistics using a dataset from Kaggle and trains an MLP Regressor model to predict a player's total points (PTS). Feature selection is performed using a Random Forest model, and the selected features are used to train the neural network.

Dataset

The dataset used in this project can be found at:
https://www.kaggle.com/datasets/justinas/nba-players-data

Prerequisites

Before running the project, ensure you have the following installed:

Python 3.7+

Jupyter Notebook (or an IDE like VS Code, PyCharm)

Required Python libraries:

pip install pandas numpy matplotlib seaborn scikit-learn

Running the Project

1. Load the Dataset

Download the dataset from Kaggle: NBA Players Data

Place the dataset file (nba_players.csv) in the working directory.

Run the script in Jupyter Notebook or Python.

2. Data Preprocessing

The script selects numerical features from the dataset.

It removes missing values and irrelevant columns.

Feature selection is performed using Random Forest.

3. Model Training

A MinMaxScaler is used to normalize the data.

The dataset is split into training and testing sets.

An MLP Regressor (Neural Network) is trained to predict total points (PTS).

4. Model Evaluation

The model is evaluated using R² Score.

The script plots feature importance for better understanding.

5. Making Predictions

The trained model predicts total points for a sample player.

Example:

Predicted PTS for Sample Player: 24.75

Results

The model predicts player performance based on their stats.

Feature importance helps understand which statistics contribute most to scoring.

Future Improvements

Implement hyperparameter tuning for better performance.

Integrate Kaggle API to fetch the dataset dynamically.

Deploy the model in a web-based interface for interactive predictions.

Following these steps will allow you to analyze NBA player performance and train a neural network for point prediction. 🚀

