# 🚲 Bike Demand Forecasting System
## Overview

This project predicts hourly bike rental demand using machine learning models.

The goal is to capture temporal patterns in historical data to help optimize bike availability.

## Dataset

Kaggle Bike Sharing Demand dataset

Features include:

* datetime

* hourly demand
* temporal patterns

## Feature Engineering

Key features used:

Hour of day
Day of week
Month
Weekend indicator
Lag features (1h, 24h, 168h)
Rolling mean demand

These features capture temporal dependencies in the demand signal.

## Models

The following models were trained:

Random Forest
XGBoost
LightGBM

Final predictions use model comparison and ensemble methods.

## Evaluation

Metrics used:

MAE (Mean Absolute Error)

Time-based train/test split was applied to prevent data leakage.

## Demo

Interactive prediction dashboard built with Streamlit.

Users can adjust time features and view predicted bike demand.

## Tech Stack

Python
Pandas
Scikit-learn
XGBoost
LightGBM
Streamlit

