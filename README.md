# Week 1: Housing Price Prediction Pipeline

This repository contains a modular machine learning workflow built to predict house prices using linear regression and ensemble models.

## Repository Architecture
1. **Data Cleaning.ipynb**: Resolves data formats and maps categorical labels safely using vectorized operations.
2. **Data loading and Exploration.ipynb**: Conducts initial statistical profiling and checks correlation strengths.
3. **Model Building and Diagram .ipynb**: Trains models, resolves hyperparameter performance, and visualizes predictions.

## Core Evaluation Findings
* **Most Influential Features**: Area, bathrooms, air conditioning, and stories drive market valuations highest.
* **Model Accuracy (Linear Regression)**: Captures 64.05% of the market variance, offering a stable baseline for standard properties.
* **Data Surprise Factor**: Significant multi-million dollar luxury outliers heavily skew predictions at the top end.
* **Business Strategy Recommendation**: Prioritize implementing air conditioning infrastructure prior to asset listing due to its high correlation (0.45) with price scaling.
