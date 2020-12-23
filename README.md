# Applied-Finance
Collection of Python projects related to finance.

### Anomaly Detection
* Constructed an LSTM autoencoder to detect anomalies in the price action of SPY (S&P500 ETF)
* Predicts anomalies for the year 2020
* Historical data starts from 01-01-2000 
* Model is up-to-date and works with current market data

**Libraries**: datetime, numpy, pandas, matplotlib, seaborn, sklearn, tensorflow, keras

**Last runtime: 12/21/2020**

### NLP Sentiment Analysis of 10K Financial Statements
* Performed sentiment analysis of 10-K financial statements over time of various stocks (e.g. AAPL, MSFT, DIS)
* Built an API to scrape financial statements from the SEC EDGAR portal
* Financial statements were explored, clean, and pre-processed (lowercase, lemmatization, removing stop words, etc.)
* Positive, negative, and uncertain sentiments were visualized over time 
* Model is up-to-date and works with the latest financial statements

**Libraries**: pickle, numpy, pandas, tqdm, ratelimit, bs4, nltk, requests, re, matplotlib, seaborn 

**Last runtime: 12/22/2020**

### Portfolio Optimization - Modern Portfolio Theory - Sharpe Ratio
* Constructed the Modern Portfolio Theory (MPT) calculating the Sharpe ratio, annualized volatility, and annualized returns of a portfolio
* Given a portfolio of stocks/cryptocurrencies, the MPT will output optimal portfolio weights to maximize the Sharpe Ratio
* Efficient frontier is constructed to visualize the Sharpe Ratios of 10000s of different portfolio weight combinations
* Model is up-to-date and works with the latest historical market data
* It is possible to add cryptocurrencies to the portfolio (use 'BTC-USD', 'ETH-USD', etc.)

**Libraries**: numpy, pandas, matplotlib, seaborn

**Last runtime: 12/21/2020**
