# Trading-Behavior-Analysis-Using-Sentiment-Data


## Overview

This project analyzes how market sentiment (Fear vs Greed) influences trading behavior and profitability. By combining trading data with sentiment data, we uncover patterns in trader decisions, risk-taking, and performance.

---

## Objective

* Understand how sentiment affects trading outcomes
* Analyze trader behavior such as trade frequency, leverage, and position bias
* Build a simple machine learning model to predict profitability

---

## Dataset

* Sentiment Data: Contains daily market sentiment classification (Fear or Greed)
* Trades Data: Contains individual trade records including PnL, size, leverage, and trade direction

---

## Steps Performed

### Step 1 Data Cleaning

* Standardized column names
* Removed duplicates and missing values
* Converted data types for consistency

### Step 2 Feature Engineering

* Daily PnL per account
* Number of trades per day
* Average trade size
* Average leverage
* Long position ratio

### Step 3 Data Merging

* Combined trading metrics with sentiment data based on date

### Step 4 Exploratory Data Analysis

* Compared PnL distribution across sentiment
* Analyzed win rates
* Studied trading behavior trends

### Step 5 Trader Segmentation

* High vs Low leverage traders
* Frequent vs Infrequent traders
* Consistent vs Inconsistent traders based on volatility

### Step 6 Machine Learning Model

* Built a Random Forest Classifier
* Predicted whether a trade day is profitable
* Used features like trade count, leverage, size, and long ratio

---

## Key Insights

* Traders tend to perform worse during Fear periods
* Greed leads to higher trading activity and increased leverage
* High leverage is associated with higher risk and potential losses
* Consistent traders show more stable performance over time

---

## Strategy Recommendations

* Reduce leverage during Fear periods
* Avoid overtrading during Greed phases
* Focus on maintaining consistency rather than high-frequency trading

---

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## How to Run

1 Install dependencies
2 Run the Python script
3 Analyze generated charts and model accuracy

---

## Conclusion

This project demonstrates how behavioral finance concepts can be applied using data analysis and machine learning to improve trading strategies.
