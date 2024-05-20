# Stock_Analysys
Stock Analysis using Python Libraries like yfinance and by web scraping 

1. Imports necessary libraries such as `yfinance`, `pandas`, `requests`, `bs4` (Beautiful Soup), and `plotly`.
2. Fetches historical stock price data for Tesla (TSLA) and GameStop (GME) using the Yahoo Finance API (`yfinance`).
3. Fetches revenue data for Tesla from a specified URL using web scraping techniques with `requests` and `BeautifulSoup`.
4. Cleans and preprocesses the fetched data, converting revenue data to numeric values and resetting the index of the DataFrame.
5. Defines a function `make_graph` that generates a plotly graph showing historical share prices and revenue for a given stock.
6. Calls the `make_graph` function to generate and display a graph for Tesla.

For your README.md file, you can include the following description:

---

## Stock and Revenue Visualization

This Python script fetches historical stock price data from Yahoo Finance and revenue data from a specified URL using web scraping techniques. It then generates visualizations comparing the historical share prices and revenue for a given stock.

### Libraries Used:
- `yfinance`: Fetches historical stock price data from Yahoo Finance.
- `pandas`: Manipulates and preprocesses data in DataFrame format.
- `requests`: Fetches HTML content from a specified URL.
- `Beautiful Soup (bs4)`: Parses HTML content for web scraping.
- `plotly`: Generates interactive visualizations.

### Functionality:
- Fetches historical stock price data for Tesla (TSLA) and GameStop (GME) from Yahoo Finance API.
- Scrapes revenue data for Tesla from a specified URL.
- Cleans and preprocesses the fetched data.
- Generates interactive visualizations comparing historical share prices and revenue for a given stock.

### Usage:
- Update the ticker symbol and URL as needed.
- Run the script to generate visualizations for the desired stock.

---

