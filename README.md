# Codveda-Technologies--Level2-Intermediate--DataAnalytics
This repository contains regression analysis and time series analysis projects completed as part of Level 2


---

## What’s Inside?

This repo includes two main Jupyter notebooks:

1. Level2_task1_regression_analysis.ipynb
2. Level 2_task 2_Time Series Analysis.ipynb

Both of them are based on the stock prices dataset, which includes daily trading data for several companies like Apple (AAPL), Amazon, etc.

Below is the link to the stock prices dataset: https://drive.google.com/file/d/1nlvOLrcDOnCKFV6FTOJ5Syf0laekYnbc/view?usp=sharing


## Task 1 – Regression Analysis

In this task, I built models to predict stock closing prices based on other variables like opening price, high, low, and trading volume.

### Steps Followed:
- Explored the dataset using .head(), .info() and .isnull().sum()
- Cleaned missing data using df.dropna()
- Focused on Apple (AAPL) data for simplicity and clarity
- Selected features: open, high, low, volume
- Target variable: close (what we want to predict)
- Trained the following regression models:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Evaluated models using metrics:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score
- Visualized actual vs predicted close prices

--- This is the link to the notebook: https://colab.research.google.com/drive/1Aa3-2SfvP99Pj22_2SuC6bH3Bx5enXYU?usp=sharing



## Task 2 – Time Series Analysis

In this task, I analyzed stock trends over time and visualized patterns in closing prices using time-based plots.

### Steps Followed:
- Filtered Apple stock prices (AAPL)
- Converted the date column to datetime format
- Set date as index for time series plotting
- Created line charts to show:
  - Closing price over time
  - Monthly trends
  - Weekly average patterns
- Used resample() to visualize long-term patterns

--- This is the link to the notebook: https://colab.research.google.com/drive/1AgoB6CfF_bdeQR93AybnKLFLn5uVxR5O?usp=sharing


## Libraries Used

- pandas
- matplotlib
- seaborn
- scikit-learn
- numpy


## Why I Chose Stock Prices

I selected the stock prices dataset because it’s rich in both numerical and time-based data — making it ideal for practicing regression and time series analysis in a real-world context.


## Feedback

If you have suggestions or feedback, feel free to open an issue or connect with me!
