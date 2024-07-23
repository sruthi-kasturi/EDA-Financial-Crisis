# EDA-Financial-Crisis

## Overview
This project focuses on exploratory data analysis (EDA) of stock prices, specifically bank stocks. The analysis covers the period from the financial crisis of 2007-2008 up to early 2016.

## Dataset
We use stock price data from Yahoo Finance for the following banks:
- Bank of America
- CitiGroup
- Goldman Sachs
- JPMorgan Chase
- Morgan Stanley
- Wells Fargo

The dataset spans from January 1, 2006, to January 1, 2016.

## Objectives
- Retrieve and clean stock price data for major banks.
- Perform exploratory data analysis to identify trends and patterns.
- Visualize stock price movements and returns.
- Analyze risk and returns for the banks over different periods.

## Analysis and Insights
### Data Retrieval
- Used pandas datareader to fetch stock price data from Yahoo Finance.

### Exploratory Data Analysis (EDA)
- Calculated the maximum closing price for each bank's stock during the period.
- Created a returns DataFrame to calculate daily returns for each bank.
- Visualized the returns using pair plots.
- Identified dates with the best and worst single-day returns for each bank.
- Analyzed the standard deviation of returns to classify risk levels for different years.
- Visualized return distributions for specific years using seaborn's distplot.

### Visualizations
- Line plots of the closing prices for each bank.
- Rolling 30-day average plots for selected banks.
- Heatmap of the correlation between the closing prices of different banks.
- Clustermap for clustering correlations.

### Additional Analysis
- Created a candle plot for Bank of America's stock for 2015.
- Plotted simple moving averages for Morgan Stanley for 2015.
- Generated a Bollinger Band plot for Bank of America for 2015.

## Technologies and Tools
- Python for data analysis and visualization
- Pandas for data manipulation
- Matplotlib and Seaborn for visualization
- pandas-datareader for fetching stock data

## How to Run the Project
1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebooks in the `notebooks/` directory to reproduce the analysis.

## Contact
For any questions or collaboration opportunities, feel free to reach out.

