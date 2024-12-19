# Tesla and GameStop Stock Analysis

In this project, I analyze the historical stock prices and revenues of Tesla and GameStop using **Python**. The data is collected from multiple sources:
- **Historical stock prices** are retrieved using `yfinance`.
- **Revenue data** is scraped from web pages using `BeautifulSoup` and processed with `pandas`.

---

## Features
### 1. **Data Extraction**
- Historical stock price data for Tesla and GameStop retrieved using `yfinance`.
- Revenue data scraped from HTML tables using `requests` and `BeautifulSoup`.

### 2. **Data Cleaning**
- Cleaned and transformed the revenue data to make it suitable for analysis (removed symbols like `$` and `,`).
- Filtered the datasets to align the date ranges for proper visualization.

### 3. **Data Visualization**
- Created clear and interactive visualizations using `plotly` to compare stock prices and revenues over time.

---

## Technologies Used
- **Python**
- Libraries:
  - `yfinance`: For extracting historical stock prices.
  - `requests`: For downloading HTML content.
  - `BeautifulSoup`: For web scraping and HTML parsing.
  - `pandas`: For data manipulation and cleaning.
  - `plotly`: For creating interactive visualizations.

---

## Learning Context

This project is part of the **IBM Data Science Professional Certificate**
The objectives include:
- Applying web scraping techniques to extract real-world data.
- Practicing data cleaning and preparation to make datasets analysis-ready.
- Developing meaningful insights through visualizations and storytelling.

I am currently in the process of deepening my knowledge and skills in Python, data manipulation, and visualization as part of my journey to becoming a professional in data.

---

## Results and Insights

### Tesla
- **Correlation**: A clear positive correlation between Tesla's revenue growth and stock price over time.
- **Insights**: Revenue and stock price trends are strongly aligned during periods of rapid growth, reflecting investor confidence in the company's financial performance.

### GameStop
- **Disconnect**: A visible disconnect between revenue trends and stock price movements, particularly during the 2021 "GameStop phenomenon".
- **Insights**: This highlights the influence of speculative trading on stock prices, independent of a company’s revenue performance.

- ## How to Use

1. Download the repository : Analyse de données-tesla-gme.ipynb
2. Open the `tesla_stock_analysis.ipynb` file in Jupyter Notebook or JupyterLab.
3. Run the cells to reproduce the analysis.
