# Predicting Air Quality Index (AQI) Using Machine Learning and Deep Learning Models
**Students:** Andrea Thomas, Joseph Edwards, Jinyuan He

## Introduction

Air pollution has become one of the most significant environmental and public health challenges in modern cities. Poor air quality is closely linked to respiratory illness, reduced life expectancy, productivity losses, and increased healthcare burden. For governments, environmental agencies, and businesses, accurate forecasting of air quality is essential for early warnings, public protection, and operational decision-making.

In this project, we focus on predicting the Air Quality Index (AQI) using the Taiwan Air Quality Dataset (2016–2024), an hourly dataset published on Kaggle. Taiwan provides an excellent case study due to its dense urban centers, complex topography, and highly variable meteorological patterns influenced by monsoon seasons, typhoons, long-range dust transport, and industrial activity. These unique characteristics make AQI prediction both scientifically interesting and practically important.

The goal of this project is to build a complete machine learning pipeline to forecast hourly AQI values based on historical pollutant concentrations and weather conditions. We construct models from three categories:

Baseline Model: Linear Regression
Tree-Based Models: Random Forest and XGBoost
Deep Learning Sequence Models: Feedforward Neural Network (FNN) and Long Short-Term Memory (LSTM)
By comparing these approaches, we aim to understand:

Which model family performs best for Taiwan's AQI patterns
Which pollutant and meteorological variables contribute most to prediction accuracy
How temporal dependencies (lag features and sequences) influence forecasting quality
This notebook includes end-to-end steps:

Data loading and exploratory analysis
Feature engineering (time features, lag features, rolling windows)
Model development across ML and DL techniques
Evaluation with MAE, RMSE, and R²
Visualization of predictions and feature importances
Ultimately, this project provides a practical and data-driven approach to AQI forecasting tailored to Taiwan's environmental context, demonstrating how machine learning and deep learning can support smarter air-quality monitoring and early-warning systems.

## Usage:
Run on Google Colab (Recommended)
Steps:
1. Click the notebook file in GitHub
2. At the top, click: "Open in Colab."
3. Once opened, run each cell from top to bottom
4. Colab will automatically install missing dependencies
