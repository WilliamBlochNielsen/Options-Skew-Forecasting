# Options-Skew-Forecasting

A quantitative trading strategy that uses machine learning to predict volatility skew changes in SPY options and generate profitable trading signals.


## Overview

This project develops a complete end-to-end system for forecasting options volatility skew using advanced machine learning techniques. The system combines traditional financial modeling with modern ML algorithms to predict changes in implied volatility patterns, enabling systematic options trading strategies.


**Key Innovation:** Using ML methods to predict options skew changes, which are notoriously difficult to forecast but highly profitable when done correctly.


## Features


The system includes comprehensive data collection from real-time SPY options chains via yfinance, sophisticated feature engineering with lagged variables, rolling statistics, and market stress indicators, multiple ML models including Random Forest, Gradient Boosting, and Ridge Regression for ensemble forecasting, robust backtesting framework with risk metrics, transaction costs, and performance analysis, and a production-ready trading system with real-time signal generation and risk management.


## Technical Approach


**Data Processing:** Real-time options data collection, cleaning, and validation with implied volatility surface modeling using polynomial fitting and multi-expiration analysis.


**Feature Engineering:** Lagged variables for skew, VIX, and price changes, rolling statistics and technical indicators, interaction features combining skew with market stress metrics, and regime detection for different market conditions.

**Machine Learning:** Random Forest for non-linear relationships and feature interactions, Gradient Boosting for sequential learning and error correction, Ridge Regression for linear relationships with regularization, and ensemble approach combining multiple models for robust predictions.


**Risk Management:** Comprehensive backtesting with realistic transaction costs, Sharpe ratio, maximum drawdown, and win rate analysis, position sizing and stop-loss recommendations, and daily workflow automation for operational deployment.


## Installation


Clone this repository with the command: git clone https://github.com/WilliamBlochNielsen/Options-Skew-Forecasting.git

And install required packages with the command: pip install yfinance pandas numpy matplotlib scipy scikit-learn datetime jupyter
