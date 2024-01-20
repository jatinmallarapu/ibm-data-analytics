# Project: Extracting and Visualizing Stock Data
## Aim:
The aim of this project is to extract essential data from a dataset and visualize it to facilitate better decision-making in the field of data science. Specifically, the project focuses on extracting stock data for Tesla (TSLA) using the yfinance library and revenue data from a website using web scraping. The extracted data is then visualized in a graph to provide insights into Tesla's historical share prices and revenue.

## Models Used:
1) yfinance (Yahoo Finance API):
Used to extract historical stock data for Tesla (TSLA).
The Ticker function is employed to create a ticker object for the specified stock symbol.
The history function is utilized to extract stock information, which is stored in a DataFrame named tesla_data.

2) BeautifulSoup and Requests (Web Scraping):
The requests library is employed to download the webpage containing Tesla's revenue data.
BeautifulSoup is used for parsing the HTML data and extracting the relevant table containing quarterly revenue data.
The extracted revenue data is then stored in a DataFrame named tesla_revenue.

3) Plotly:
Utilized for creating interactive and visually appealing graphs.
The make_subplots function is used to create a subplot with two charts: one for historical share prices and the other for historical revenue.
The Scatter function is employed to plot the historical share prices and revenue over time.

## Usage in Daily Scenario:
This project is beneficial for individuals, investors, and financial analysts who are interested in analyzing Tesla's stock performance and revenue trends. Users can input different stock symbols and explore historical data, providing valuable insights for investment decisions. The interactive graph allows for a dynamic visualization of the relationship between share prices and revenue, aiding in identifying patterns and making informed decisions.

## Conclusion:
The project demonstrates the use of various Python libraries, such as yfinance for financial data extraction, BeautifulSoup for web scraping, and Plotly for interactive visualization. The combination of these tools enables users to gain insights into historical stock performance and revenue trends. The code can be extended to analyze and visualize data for other stocks, making it a versatile tool for financial analysis.
