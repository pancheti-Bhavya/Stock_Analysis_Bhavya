## 📊 Stock Market Analysis 


## Project Overview:

This project analyzes historical stock market data to uncover trading patterns, evaluate company performance, and generate business insights using a complete Data Engineering pipeline.


- Python-based ETL processing
- Data cleaning & business rule validation
- MySQL data modeling & analytics
- Technical indicators (Volatility, Moving Averages)
- Business insights generation
- Data visualization dashboards




## PROJECT WORKFLOW

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


## Tech Stack
Python	Data Processing & ETL
Pandas	Data Cleaning & Transformation
NumPy	Numerical Calculations
MySQL	Data Storage & SQL Analytics
Matplotlib	Data Visualization

## OBJECTIVES

Identify reliable stocks using historical data
Analyze and predict stock price trends
Understand factors influencing stock movement

## BUSINESS RULES APPLIED

## 1.Missing Values Handling
close_price → Median per stock
volume → 0
high_price → max(open, close)
low_price → min(open, close)
## 2.Price Sanity Checks
high ≥ open & close
low ≤ open & close
## 3.Trend Classification
UP / DOWN / NO_CHANGE

## TECHNICAL ANALYSIS PERFORMED

Daily closing price trends
Volatility analysis using daily returns
Volume vs price movement correlation
Moving averages (7-day & 30-day)

## Outcomes

Cleaned and validated stock dataset
Technical analysis visualizations
Performance comparison across stocks
Investment-oriented insights

## 🖼️ Visualizations

1.Plot daily closing price trends per stock

<img width="886" height="563" alt="Screenshot 2026-02-19 184753" src="https://github.com/user-attachments/assets/a26e5b1f-3c42-4779-9f12-77c9c977645a" />

<img width="1008" height="568" alt="Screenshot 2026-02-19 184820" src="https://github.com/user-attachments/assets/7f2648f1-1829-4b59-8187-3394e7705a3c" />

<img width="1084" height="581" alt="Screenshot 2026-02-19 184827" src="https://github.com/user-attachments/assets/71d9a734-f71b-4362-ad8b-22752ed475c6" />

2.Identify Highest Volatility Stock

<img width="907" height="566" alt="Screenshot 2026-02-19 184855" src="https://github.com/user-attachments/assets/c7a673b5-1af0-40fc-ba17-7955a861507e" />

3.Volume vs Price Movement Correlation

<img width="927" height="584" alt="Screenshot 2026-02-19 184906" src="https://github.com/user-attachments/assets/7cd0d632-aa58-4f8b-b016-f5c4ec1df26a" />

<img width="996" height="555" alt="Screenshot 2026-02-19 184914" src="https://github.com/user-attachments/assets/29f9b2ed-c6ee-4f2d-ab9b-fb4c3883393e" />

<img width="985" height="562" alt="Screenshot 2026-02-19 184923" src="https://github.com/user-attachments/assets/016ed005-cc21-48a0-9ae1-96c551c81e82" />

4.Moving Averages (7-Day & 30-Day)

<img width="914" height="564" alt="Screenshot 2026-02-19 184946" src="https://github.com/user-attachments/assets/ae8dc416-aff6-4b7e-bf9e-27e989a9ae31" />

<img width="967" height="557" alt="Screenshot 2026-02-19 185526" src="https://github.com/user-attachments/assets/4f80bd4b-583c-4b82-908c-8dc111dc7317" />

<img width="973" height="556" alt="Screenshot 2026-02-19 185535" src="https://github.com/user-attachments/assets/914add09-7312-442f-bc53-e52cb2205e99" />




