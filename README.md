# Stock Price Movement Prediction and Trading Strategy Backtesting

This repository contains a complete workflow for predicting stock price movements and evaluating trading strategies using machine learning and deep learning models. The project focuses on Apple Inc. (AAPL) stock and includes feature engineering, model training, optimization, and backtesting with realistic transaction costs.

---

## Project Overview

This project aims to develop models that predict next-day stock price direction based on technical indicators and test their effectiveness in a simulated trading environment.

### Key Components:
- Data preprocessing and feature engineering from historical stock data
- Binary classification target creation (price up/down)
- Model training and evaluation with:
  - Random Forest
  - XGBoost
  - LSTM (Long Short-Term Memory network)
- Hyperparameter tuning and optimization
- Trading strategy backtesting including transaction costs
- Performance comparison of models via classification metrics and cumulative returns

---

## Results Summary

- **Random Forest and XGBoost** showed moderate classification accuracy and modest returns.
- **LSTM model** leveraging time-series sequences significantly improved classification metrics and achieved a strong cumulative return (18.25%) with a Sharpe ratio of 3.5.
- Backtests include realistic transaction costs and risk metrics like maximum drawdown.

---

## Getting Started

### Requirements
- Python 3.8+
- Libraries: pandas, numpy, scikit-learn, xgboost, tensorflow, matplotlib, seaborn

### Usage

1. Clone the repo
2. Prepare your dataset (`AAPL_preprocessed.csv` expected format)
3. Run the notebook/scripts sequentially:
   - Feature engineering and data preprocessing
   - Model training and evaluation (Random Forest, XGBoost)
   - Backtesting trading strategy
   - LSTM model training and evaluation
4. Review performance metrics and visualizations

---

## File Structure

- `task1_data_preprocessing.ipynb` — Data cleaning and feature engineering  
- `task2_model_training_evaluation.ipynb` — Random Forest and XGBoost model building  
- `task3_backtesting_strategy.ipynb` — Backtesting strategy based on model predictions  
- `task4_hyperparameter_tuning.ipynb` — Model optimization and final evaluation  
- `bonus_lstm_model.ipynb` — LSTM model implementation and improved results  
- `AAPL_preprocessed.csv` — Sample processed dataset (if allowed to share)

---

## Acknowledgements

- Technical indicators calculated based on financial market analysis best practices
- LSTM implementation inspired by common time series forecasting approaches in finance

---

## License

[MIT License](LICENSE)

---

Feel free to reach out for any questions or collaborations!
