# Bitcoin-Price-Sentiment-Analysis
This project tracks Bitcoin's live price using web scraping and performs sentiment analysis based on price movements.
It also saves the data into a CSV file and visualizes price trends with sentiment indicators.

🚀 Project Overview

This project does the following:

✔ Scrapes real-time Bitcoin price from CoinMarketCap
✔ Calculates percentage change from the previous price
✔ Assigns sentiment: Positive, Negative, or Neutral
✔ Saves timestamped data to a CSV file
✔ Automatically updates every 1 minute using APScheduler
✔ Visualizes price movement with sentiment colors on a graph

🧠 Tech Stack

Python
BeautifulSoup (Web Scraping)
Requests
Pandas
APScheduler
Matplotlib
