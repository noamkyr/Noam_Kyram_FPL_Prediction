# FPL Points Predictor

This project is designed to predict Fantasy Premier League (FPL) points for players based on historical data and upcoming fixtures. The model considers various factors such as player performance, opponent strength, and match location to make predictions. It’s a powerful tool for FPL enthusiasts who want to optimize their teams and make data-driven decisions.

## Features

- **Data Extraction**: Gathers historical player and team performance data from the FPL API and upcoming game data.
- **Data Processing**: Cleans and preprocesses data, filtering for relevant player statistics and fixtures.
- **Prediction Model**: Utilizes a custom algorithm to forecast FPL points based on historical data, expected goals (xG), and assists (xA). The model predicts the players' FPL score in the next gameweek.
- **Visualization**: Provides insightful visualizations of player performance trends and upcoming match difficulties.

## Technologies Used

- **Python**
- **Pandas**: Data processing and manipulation.
- **NumPy**: Numerical computations and operations.
- **Matplotlib**: Visualization of data and predictions.
- **SciKit-Learn**: Machine learning algorithms for predictive modeling.
- **FPL API**: Source of historical player data.
