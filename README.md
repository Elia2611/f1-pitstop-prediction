# F1 Pit Stop Prediction - Kaggle Challenge

This project uses **XGBoost** with **CUDA GPU** acceleration to predict Formula 1 pit stop strategies.

## Project Structure
- `f1-pitstop-prediction.ipynb`: Main notebook with EDA, GridSearch, and model evaluation.
- `requirements.txt`: Python dependencies.

## Key Features
- **Exploratory Data Analysis (EDA)** with Seaborn.
- **Hyperparameter Tuning** using `GridSearchCV`.
- **ROC-AUC Evaluation** to measure model performance.

## How to use
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Download the data from the [Kaggle Playground Series S6E5](https://www.kaggle.com/competitions/playground-series-s6e5).
