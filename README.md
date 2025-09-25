# stocks-webscraping-api

🔹 Introduction

This project demonstrates the implementation of web scraping techniques to extract real-time financial data from Google Finance – Most Active Stocks.
We specifically targeted the 50 most actively traded public companies, aiming to show practical applications of:

Data collection in financial analytics

Integration with financial APIs

Actionable insights into market behavior

Key metrics collected include:

Company name & stock ticker

Current stock prices & intraday ranges

Trading volume (market interest)

Daily price change & percentage change

🔹 Methodology
1. Web Scraping

Source: Google Finance – Most Active Stocks

Extracted data points using HTML class tags:

sbnBtf → List of stocks

COaKTb → Company names

ZvmM7 → Ticker symbols

BAftM → Current prices

JwB6zf → Price changes (+/–)

2. API Integration

Integrated with TwelveData API
 for enriched stock information:

Opening price

Highest & lowest intraday prices

Closing price

Trading volume

3. Data Processing

Cleaned and structured data using Pandas

Combined web-scraped + API data into a unified DataFrame

Prepared outputs for further visualization & analysis

🔹 Key Insights

Identified stocks with high volatility (potential risk/reward opportunities)

Recognized consistent upward/downward trends (potential entry/exit points)

Built a framework to compare market activity vs. trading performance

🔹 Conclusions

By extracting and combining data from Google Finance and TwelveData API, this project:

Offers a comprehensive intraday view of stock price behavior

Helps in risk assessment, pattern recognition, and strategy development

Provides a scalable foundation for building financial dashboards or automated trading signals

🔹 Tech Stack

Python 3.x

Libraries: Pandas, BeautifulSoup, Requests, JSON, Matplotlib (if used)

APIs: TwelveData API

Tools: Jupyter Notebook

🔹 Future Improvements

Automate daily data scraping & updates

Add interactive visualizations (Plotly/Seaborn)

Expand API integration for broader financial metrics

Deploy as a dashboard (Streamlit/Flask)

## Acknowledgment
This project was originally developed as part of CIS 9340 (Programming for Data Analytics) at Baruch College in collaboration with Kejsi Beqiraj and Mahfuza Sabiha.
