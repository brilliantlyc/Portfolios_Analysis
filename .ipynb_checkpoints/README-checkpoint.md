# Pandas Homework: A Whale Off the Port(folio)
This is an analysis notebook tool that performs analysis and visualizations on the metrics of various portfolios including some "whale" investors' portfolios, algorithmic portfolios, and custom portfolio of stocks. The performance of the portfolios are compared to each other and to the the S&P TSX 60 Index.

## Technologies
The technologies required to use this project include: python 3.7 and pandas with the numpy, datetime, Path from pathlib, and seaborn libraries. As well as the %matplotlib function.

## Examples
The data is read from CSV files containing either daily returns or close prices, and added to DataFrames. The data is cleaned in preparation for analysis. Then, quantitative analysis is completed which includes: performance analysis, risk analysis, rolling statistic, and Sharpe Ratios.

![Sharpe Ratios](Images/SharpeRatiosExample.jpg)