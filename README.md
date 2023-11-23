# Stock-Price-Prediction-with-LSTM-and-GRU

This repository contains code for predicting stock prices of IBM using Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) models.

Overview

Stock market data can be both fascinating and lucrative for analysis. This repository includes historical stock price data for 29 of the 30 DJIA companies over the past 12 years.

It offers two formats of data presentation: a comprehensive dataset spanning from 2006-01-01 to 2018-01-01 and a smaller version focusing on data from 2017-01-01 to 2018-01-01.

These datasets comprise stock prices at market open, highest and lowest prices reached, closing prices, volume of shares traded, and the respective stock ticker names.

File Structure

all_stocks_2006-01-01_to_2018-01-01.csv: Comprehensive dataset spanning 13 years.

all_stocks_2017-01-01_to_2018-01-01.csv: Compact dataset covering the past year.

individual_stocks_2006-01-01_to_2018-01-01: Folder containing individual stock data files labeled by their ticker names.

Content Details

Columns

Date: Format: yy-mm-dd

Open: Stock price at market open (in USD)

High: Highest price reached during the day

Low: Lowest price reached during the day

Close: Closing price

Volume: Number of shares traded

Name: Ticker name of the stock

Usage

The code provided in this repository demonstrates the implementation of LSTM and GRU models for predicting IBM's stock prices. Users can leverage these models to explore predictions and further refine them for other stocks or datasets.
