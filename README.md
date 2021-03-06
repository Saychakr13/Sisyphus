# Sisyphus
AI that sees the stock market.


This is the data repository for mini project: Prediction of stock market and stock market analysis using machine learning.

File created: Sunday, August 4, 2019. 1340 hours Indian Standard Time.
***
Range of data: **July 2009- 31 December 2018**. All the datasets have some data before or after, but this time range is common between all of them. **(Except Nifty 50 data)**
***
***File contents***

cpi.csv: csv file showing yearly change in inflation rate for G20 countries **for the previous year (2008-2017)**

BSE_indices_data.csv: BSE Index data for 5 different indices. There are two categories: data based at 100 and real data

nifty50twoyearsrecentdata.csv: Index data of Nifty 50 from October 3, 2017 to September 30, 2019

monthly-crude-oil-price.csv: Crude oil price in the date range

nomintr.csv: Nominal effective exchange rate for G20 countries **for the previous year (2008-2017)**

**data/: Contains all the results of the prediction system.**

***
**Sources of data:**
***
Principal Global Indicators- Product of the Inter-Agency Group on Economic & Financial Statistics

http://www.principalglobalindicators.org


The above is an absolute gold mine of data. the Yearly-market-sector-indicator-for-g20.odf file is just a fraction of the presentable dataset.
***
***
Asia Index Pvt. Ltd.

https://www.asiaindex.co.in/indices/equity/

The above is the source for index data.
***
***
NSE of India Website

https://www.nseindia.com/products/content/equities/indices/historical_index_data.html

The source for Nifty 50 data
***
***
# LSTM
Long Short-Term Memory (LSTM) models are a type of recurrent neural network capable of learning sequences of observations.

This may make them a network well suited to time series forecasting.

An issue with LSTMs is that they can easily overfit training data, reducing their predictive skill.

Dropout is a regularization method where input and recurrent connections to LSTM units are probabilistically excluded from activation and weight updates while training a network. This has the effect of reducing overfitting and improving model performance.
***
