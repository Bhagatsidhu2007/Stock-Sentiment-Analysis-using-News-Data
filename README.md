# Stock-Sentiment-Analysis-using-News-Data
This project analyzes how public sentiment in financial news articles affects stock prices. Using a BERT-based sentiment analysis model, it evaluates daily news headlines related to a specific stock (e.g., Apple), assigns sentiment scores, and compares them to actual stock performance. It includes:

* Fetches the latest 30 days of news using NewsAPI based on a company keyword.

* Uses a Hugging Face BERT model to classify sentiment in news headlines.

* Aggregates daily sentiment scores and resamples missing values.

* Retrieves historical stock prices from Yahoo Finance.

* Plots sentiment trends alongside stock price movements.

* Calculates Pearson correlation and RMSE to understand sentiment-price relationships.

This project shows how LLMs and financial data can be combined to explore stock market sentiment trends.


