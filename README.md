# ML_Quant_Fund

A systematic research and backtesting framework for building and evaluating small-cap and mid-cap alpha strategies.
The project is designed to support factor-based models, machine learning ranking models, and portfolio construction with a focus on realistic walk-forward evaluation and low turnover.

Features

Data Handling

Fetch and preprocess equity & ETF data (e.g., from Yahoo Finance / other APIs).

Factor and feature engineering modules for systematic signals.

Models

Support for XGBoost and LightGBM Ranker.

Walk-forward training and evaluation.

Feature importance and SHAP explainability.

Backtesting

Walk-forward backtest engine with rolling train/validation windows.

Benchmark comparison against ETFs (e.g., Nifty 50, SPY).

PnL visualization and performance metrics.

Portfolio Construction

Stock ranking based on model scores.

Equal-weight / custom weighting schemes.

Risk controls and turnover monitoring.
