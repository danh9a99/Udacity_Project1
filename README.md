# Writing-a-Data-Scientist-Blog-Post

## Prerequisites

The code is saved in ```.ipynb``` file and can be run with any tool that support this file format. These are libraries that is used in this project:

- pandas
- numpy
- matplotlib
- seaborn
- warnings

### This project aims to answer these questions:

- What are two of biggest coins?
- What is the distribution of Bitcoin and Tether?
- How is the trend of Tether coin?
- How is the trend of Bitcoin coin?
- Which elements did they affect on volume of bitcoin?
- Which elements did they affect on volume of Tether?

### Results
For the code, please check the notebook ```Project_BlogPost.ipynb```.

The findings of this project already published follow the link:

https://medium.com/@narutodn19999/d500e94e3c11

### Data:
This project use data from crypto_dataset.csv that I already uploaded

## Dataset

This is a dataset of over 50 Cryptocurrencies' historical OHLC (Open High Low Close) data. The date range is from May 2013 to October 2022 on a daily basis. The dataset includes 6 variables such as open, high, low, close, volume, marketCap, timestamp, crypto_name, date.

* open: Opening price on that particular date (UTC time)
* high: Highest price hit on that particular date (UTC time)
* low: Lowest price hit on that particular date (UTC time)
* close: Closing price on that particular date (UTC time)
* volume: Quantity of asset bought or sold, displayed in base currency
* marketCap: The total value of all the coins that have been mined. It's calculated by multiplying the number of coins in circulation by the current market price of a single coin
* timestamp: UTC timestamp of the day considered
* crypto_name: Name of the cryptocurrency
* date: timestamp converted to date

## Summary of Findings

After investigation, the slide is to present about which elements were they that affected on pirce of crypto. Firstly, I will choose two coins that had the largest volume. Then, line charts will show us the trend of these coin through historical data. Finally, variate and multivariate exploration will show the effect of other elements on price of coins (low, high, open price).

## Key Insights for Presentation

Current values (market cap) did not affect on the number of coin buyers. Thus, I conclude that coins are more and more popular with investors. Besides, coins are quite difficult to predict the trend because of no reports as bond or stock so buyers based on upward trend of the coins to invest. That is reason why price did not affect on volume of coins.
