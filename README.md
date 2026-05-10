# B9W1: Predicting Price Moves with News Sentiment

## Project Overview

This project explores whether financial news sentiment and text patterns can help predict stock market movements. It is developed for Nova Financial Solutions to combine Natural Language Processing (NLP) with financial time-series analysis. The workflow includes financial news headline analysis, stock market historical data analysis, technical indicators, and keyword extraction from news data.

## Business Objective

The objective is to determine whether patterns in financial news can provide useful signals for predicting stock price movements and market behavior.

## Project Structure

news-sentiment-analysis/
├── notebooks/
│   ├── task1_eda.ipynb
│   ├── task2_stock_analysis.ipynb
├── data/
│   └── raw/
│       ├── financial_news.csv
│       ├── sample_stocks.csv
│       ├── sample_stock2.csv
├── src/
├── scripts/
├── requirements.txt
└── README.md

## Task 1: Financial News Analysis (EDA)

The following steps were performed: data cleaning and preprocessing, news volume trend analysis, publisher distribution analysis, and keyword extraction using CountVectorizer.

Key findings include that news spikes occur during major financial events, earnings-related terms dominate headlines, and technology companies such as Apple and Tesla appear frequently in the dataset.

## Task 2: Stock Market Analysis

This section includes loading historical stock data and computing technical indicators such as Moving Average (MA20 and MA50), Relative Strength Index (RSI), and MACD (Moving Average Convergence Divergence).

Key insights show that moving averages help smooth volatility, RSI identifies overbought and oversold conditions, and MACD signals momentum shifts and trend reversals.

## Technologies Used

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn (CountVectorizer), Jupyter Notebook, Git and GitHub.

## How to Run the Project

1. Clone the repository using git clone.
2. Install dependencies using pip install -r requirements.txt.
3. Open Jupyter Notebook and run task1_eda.ipynb and task2_stock_analysis.ipynb.

## Key Findings

Financial news is concentrated around earnings and market events. Stock trends become clearer when technical indicators are applied. News keywords show strong influence from the technology sector and corporate performance.

## Next Steps

Future work includes sentiment analysis using NLP tools such as VADER or TextBlob, correlation analysis between sentiment and stock returns, and building predictive models for stock price movement.