# Forecasting Canadian Wage Rates Using Time Series Models

## Overview

This project applies multiple time series forecasting techniques to model and predict monthly average hourly wage rates in Canada. The objective is to compare different forecasting frameworks and evaluate their predictive performance using out-of-sample testing.

## Methodology

- Seasonal Decomposition + ARMA (STL-Based Approach)
- SARIMA (Box-Jenkins Methodology)
- Holt-Winters Exponential Smoothing
- Mean Squared Prediction Error (MSPE)

## Key Findings

- The STL decomposition combined with ARMA modeling achieved the lowest out-of-sample error (MSPE = 0.0135), outperforming alternative approaches
- The selected SARIMA(0,1,0)(0,1,1)[12] model captured seasonal structure effectively but produced higher forecast error (MSPE = 0.0321)
- The Holt–Winters additive model generated stable forecasts under consistent trend and seasonality but had slightly higher error (MSPE = 0.0327)
- Decomposition-based modeling provided the strongest balance between interpretability and predictive accuracy

## Usage
1. Clone the repository
2. Install required R packages
3. Run scripts in numerical order 
