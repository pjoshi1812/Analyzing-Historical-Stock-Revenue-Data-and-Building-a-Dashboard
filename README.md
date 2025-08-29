📈 Extracting and Visualizing Stock Data

This project demonstrates how to extract stock price data and revenue data for Tesla (TSLA) and GameStop (GME), clean the datasets, and visualize them using Plotly.

It covers key concepts of data extraction, web scraping, cleaning, and visualization.

📂 Table of Contents

Define a Graphing Function

Extract Tesla Stock Data (using yfinance)

Extract Tesla Revenue Data (using Web Scraping)

Extract GameStop Stock Data (using yfinance)

Extract GameStop Revenue Data (using Web Scraping)

Visualize Tesla Stock and Revenue

Visualize GameStop Stock and Revenue

⚙️ Technologies Used

Python 🐍

yfinance
 – Extracting stock data

BeautifulSoup
 – Web scraping

Pandas
 – Data cleaning and manipulation

Plotly
 – Interactive data visualization

🚀 Steps Performed
1. Define Graphing Function

A reusable function make_graph() was defined to visualize historical stock prices and revenues in two subplots.

2. Extract Stock Data

Used yfinance.Ticker() to create objects for:

Tesla (TSLA)

GameStop (GME)

Retrieved stock history with period="max".

3. Extract Revenue Data

Scraped revenue tables from provided HTML pages:

Tesla: revenue.htm

GameStop: stock.html

Cleaned revenue values by removing $ and ,.

4. Visualize Data

Plotted stock price vs revenue for Tesla and GameStop (data limited up to June 2021).

Used Plotly for interactive graphs.

📊 Sample Graphs
Tesla Stock vs Revenue

(Stock Price and Revenue until June 2021)

GameStop Stock vs Revenue

(Stock Price and Revenue until June 2021)

📌 How to Run

Install dependencies:

pip install yfinance beautifulsoup4 html5lib plotly pandas


Run the Jupyter Notebook:

jupyter notebook


Open the notebook and execute cells step by step.

📝 Author

👩 Prajakta Joshi
