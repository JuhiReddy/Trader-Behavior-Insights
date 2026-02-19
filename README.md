# Trader Performance vs Market Sentiment Analysis

This project analyzes how Bitcoin market sentiment (Fear vs Greed) impacts trader
performance and behavior using historical trade data. The analysis focuses on
identifying performance differences, behavioral changes, and trader segments under
varying sentiment conditions.


## Features

- Daily trader-level performance analysis (PnL, win rate, trade frequency)
- Behavior analysis based on market sentiment (trade count, position size, long/short bias)
- Trader segmentation:
  - High-frequency vs low-frequency traders
  - Consistent vs inconsistent traders (based on win-rate stability)
- Actionable strategy recommendations derived from data
- Bonus:
  - Baseline predictive model (Logistic Regression)
  

## Project Setup

### Requirements
- Python 3.8 or higher
- Jupyter Notebook

### Install Dependencies
Create and activate a virtual environment (optional but recommended):

```bash
python -m venv venv
.\venv\Scripts\activate   # Windows
# source venv/bin/activate  # macOS/Linux


## How to Run

1. Open the Jupyter Notebook:
```bash
jupyter notebook analysis.ipynb
