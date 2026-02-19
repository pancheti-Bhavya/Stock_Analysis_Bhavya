# Stock_Analysis_Bhavya

Stock Market Analysis – Python and SQL Project
Project Overview:
This project analyzes historical stock market data to:
Identify trading patterns
Perform technical analysis
Generate business insights
Apply data cleaning using business rules
Build SQL analytics queries
Visualize trends using Python
-----------------------------------------------------------------------------------------------------------------
OBJECTIVES

Identify reliable stocks using historical data
Analyze and predict stock price trends
Understand factors influencing stock movement
----------------------------------------------------------------------------------------------------------------
PROJECT WORKFLOW

Data Loading
      ↓
Duplicate Removal
      ↓
Missing Value Treatment
      ↓
Price Sanity Checks
      ↓
Daily Return Calculation
      ↓
Trend Classification
      ↓
Technical Analysis
      ↓
Business Insights
-------------------------------------------------------------------------------------------------------------------------
BUSINESS RULES APPLIED

Missing Values Handling
close_price → Median per stock
volume → 0
high_price → max(open, close)
low_price → min(open, close)
Price Sanity Checks
high ≥ open & close
low ≤ open & close
Trend Classification
UP / DOWN / NO_CHANGE
-----------------------------------------------------------------------------------------------------------------
TECHNICAL ANALYSIS PERFORMED

Daily closing price trends
Volatility analysis using daily returns
Volume vs price movement correlation
Moving averages (7-day & 30-day)
------------------------------------------------------------------------------------------------------------------
OUTCOMES

Cleaned and validated stock dataset
Technical analysis visualizations
Performance comparison across stocks
Investment-oriented insights
-----------------------------------------------------------------------------------------------------------------
Output:
