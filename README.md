# Demand Forecasting with LSTM

## Overview
Predicts daily bakery sales using an LSTM neural network.

## Requirements
- Python 3.8+
- TensorFlow
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Install
pip install tensorflow pandas numpy scikit-learn matplotlib seaborn

## Data
Download from: https://www.kaggle.com/datasets/matthieugimbert/french-bakery-daily-sales
Put the CSV file in the data/ folder and rename it to: 'french_bakery_daily_sales'.

## Run
0. Ensure 'results' folder is empty.
1. Open bakery_lstm.ipynb in Jupyter Notebook
2. Run all cells from top to bottom
3. Check results/ folder for outputs

## Output (Delete files inside of 'results' folder before output can generate)
- predictions_comparison.png (actual vs predicted plot)
- training_history.png (loss over epochs)
- model_comparison.csv (metrics table)
- lstm_model_.h5 (saved model)