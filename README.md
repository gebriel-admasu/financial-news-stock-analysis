# Financial News and Stock Analysis

This project performs a **quantitative analysis** to explore the relationship between **financial news sentiment** and **stock market movements**. By analyzing news headlines and stock price data, the project aims to establish correlations between the sentiment of news articles and stock price changes.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Folder Structure](#folder-structure)
4. [Data Sources](#data-sources)
5. [Usage](#usage)
6. [Steps Completed](#steps-completed)
7. [Results and Visualizations](#results-and-visualizations)
8. [Contributing](#contributing)
9. [License](#license)
10. [Acknowledgments](#acknowledgments)

---

## Project Overview

This project focuses on performing a **quantitative analysis** using **news articles** and **stock price data**. The key tasks are:
- **Sentiment Analysis** on financial news headlines.
- **Quantitative analysis** of stock price movements.
- **Correlation analysis** between news sentiment and stock returns.

By completing these tasks, the goal is to determine whether **positive or negative news sentiment** correlates with **stock price movements** and to visualize these relationships.

---

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/gebriel-admasu/financial-news-stock-analysis.git

2. **Navigate to the project directory**:
   ```bash
   cd financial-news-stock-analysis
3. **Create and activate a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/MacOS
   venv\Scripts\activate     # Windows

4. **Install the dependencies**:
   ```bash
   pip install -r requirements.txt

---

## Folder Structure


```
    financial-news-stock-analysis/
    │
    ├── data/                          # Data folder
    │   ├── yfinance_data/             # Stock data CSV files (AAPL, MSFT, etc.)
    │   ├── historical_data/           # News data CSV files
    │
    ├── src/                           # Source code for analysis
    │   ├── sentiment_analysis.py      # Sentiment analysis code using TextBlob
    │   ├── stock_analysis.py          # Stock price analysis and calculation
    │
    ├── notebooks/                     # Jupyter Notebooks for analysis
    │   ├── exploratory_data_analysis.ipynb
    │
    ├── README.md                      # Project README
    ├── requirements.txt               # List of project dependencies
    └── .gitignore                     # Git ignore file

    ```

---

## Data Sources

Stock Data: Historical stock data fetched using Yahoo Finance (yfinance).
News Data: Financial news articles containing:
headline: Title of the article.
date: Date and time of publication.
stock: Related stock ticker symbol.

---

## Usage
```

Step 1: Data Alignment
Merge stock data and news data by aligning them on the date column.
Step 2: Sentiment Analysis
Use TextBlob to analyze headlines and compute sentiment polarity scores:
Positive: Polarity > 0
Negative: Polarity < 0
Neutral: Polarity = 0
Step 3: Daily Stock Returns
Calculate the daily percentage change in stock prices using the Close column.
Step 4: Correlation Analysis
Compute the Pearson correlation coefficient between:
Average daily news sentiment scores.
Daily percentage change in stock returns.
Step 5: Visualization
Generate scatter plots to visualize the relationship between sentiment scores and stock returns.
```

---


## Steps Completed

```
Task 1: Git Setup and Version Control

Git environment initialized and code structured in a clean manner.
Task 2: Quantitative Analysis

Technical indicators calculated for stock prices (SMA, RSI, MACD).
Stock data explored and visualized.
Task 3: Correlation Between News and Stock Movement

Aligned stock data and news data by date.
Performed sentiment analysis on headlines.
Calculated daily stock returns and correlation between sentiment scores and stock returns.
```
---

## Contributing

Contributions are welcome! Follow these steps to contribute:

Fork the repository.
Create a new branch (git checkout -b feature-name).
Commit your changes (git commit -am 'Add new feature').
Push to your branch (git push origin feature-name).
Open a Pull Request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgments
Special thanks to Kifiya AI Mastery for providing the opportunity to work on this insightful challenge.


