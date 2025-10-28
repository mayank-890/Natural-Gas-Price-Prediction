# Natural-Gas-Price-Prediction
This project focuses on analyzing and forecasting natural gas purchase prices using historical monthly data from October 2020 to September 2024. It applies fundamental data analysis and regression techniques to understand market trends and estimate prices for any date  both past and up to one year into the future.
This project analyzes historical natural gas purchase prices (Oct 2020 – Sep 2024)
and predicts future prices for up to one year ahead using a Linear Regression model.

## 🔍 Overview
- Cleaned and analyzed monthly gas price data.
- Trained a regression model to learn the price trend.
- Built a simple estimator function that predicts price for any date.

## 🧠 Tech Stack
Python · Pandas · NumPy · Scikit-learn · Matplotlib

## 📊 Example Usage
```python
from model_training import estimate_price
print(estimate_price("2025-06-01"))
