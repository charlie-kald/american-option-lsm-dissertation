# Longstaff–Schwartz American Option Pricing

This repository contains the Python implementation developed for my MSc Data Analytics dissertation on Longstaff–Schwartz Monte Carlo (LSM) pricing of American options.

## Project Overview

The project investigates how continuation-regression choice affects American option pricing accuracy, early-exercise boundary stability, and Greek estimation within the Longstaff–Schwartz framework.

The implementation validates the LSM model against established option-pricing benchmarks before comparing alternative polynomial and weighted Laguerre regression specifications.

## Main Analysis

The notebook includes:

- Longstaff–Schwartz Monte Carlo pricing of an American put option
- Validation against Black–Scholes and Cox–Ross–Rubinstein benchmarks
- Monte Carlo path and exercise-date convergence analysis
- Comparison of polynomial and weighted Laguerre continuation regressions
- Out-of-sample regression evaluation
- Early-exercise boundary estimation and stability analysis
- Delta, Gamma, and Vega estimation using finite differences
- Comparison of full-refit and fixed-policy Greek estimation
- Smoothed local price-curve estimation for improving Gamma stability
- Integrated regression-model comparison
- Extension to a two-asset American minimum-put option

## Key Findings

Regression choice involves important trade-offs between pricing accuracy and numerical stability. Quadratic regression produced the most stable early-exercise boundary, while Weighted Laguerre Order 3 provided the strongest overall balance across pricing, boundary, and Gamma performance.

Gamma was particularly sensitive to Monte Carlo and exercise-policy noise. A smoothed local price-curve estimator substantially reduced cross-seed Gamma variability relative to the traditional three-point finite-difference estimator.

The multi-asset extension demonstrated how the validated LSM framework can be extended to higher-dimensional American option pricing problems.

## Technologies

- Python
- NumPy
- pandas
- Matplotlib
- Jupyter Notebook

## Repository Contents

- `Dissertation Final.ipynb` — Complete implementation, analysis, results, and visualisations

## Author

Charles Kaldor  
MSc Data Analytics  
Queen's University Belfast
