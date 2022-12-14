### Project Title
Stock Performance prediction

#### Executive summary
Introduction, Purpose, Key points of the report, key risks
S&P 500 (Standard and Poor's 500) is a stock market index that tracks the performance of 500 publicly listed US companies. Several criteria are used in choosing which companies belong to the S&P 500. Market Capitalization is one of the most important criteria but other requirements are also considered. The S&P 500 is used as a general market indicator.

When deciding to buy a stock, investors take many factors into account. One of these is a stock's past performance. How far back you want to look depends on the industry, investment strategy and personal preference. I picked about a little over ten years since this time horizon allows for seeing how the stock performs over several bull and bear markets. 

#### Rationale
Investing is an effective way to have your money work for you and build wealth. In order to get the best results, it is important to choose wisely what to invest in. Stocks are one of the best investments to include in your investment portfolio, since they yield higher returns than many other options. However, it can be riskier than other investments such as funds, bonds, and savings account, so it's important to look carefully at a company before investing in it, after all you are buying ownership in this company and giving them your money. 

#### Research Question
We are trying to predict which stock within a given industry will have the best performance. The criteria we will use for this will be the daily adjusted closing prices. We will be using historical prices from the past 12 years to forecast future performance. It is important to compare stocks within the same industry since industries vary a lot in terms of what is considered good or bad in terms of financials. For this project, I picked the airline industry. We will be trying to predict which airline's stock within the S&P 500 will perform the best.  

While it is advisable to incorporate fundamental analysis and technical analysis as well as consider external factors such as the larger economy, investor sentiment, supply-chain issues, the company's future plans, etc. that is beyond the scope of this project and should be investigated personally before buying (or selling) any stock(s). However, picking out high-performers can be a good starting point to decide which stocks might be worth further investigation or simply as an additional bit of information when try to decide among your final choices. 


#### Data Sources
I am using several datasets from Kaggle. The datasets are updated daily and can be found at: https://www.kaggle.com/datasets/andrewmvd/sp-500-stocks

You can download the exact dataset I used from my google drive:
https://drive.google.com/drive/folders/1nXFWfa6ry2OG3jt-9Oxwv87u7rN5dsvG?usp=sharing

Datasets:
List of companies in the S&P 500. Compiled in sp500_companies.csv
Daily stock price data of S&P 500 companies. Compiled in sp500_stocks.csv 
 
#### Methodology
The following methods are being used:

ARIMA

XGBoost was also tried but results were poor and so it wasn't included here. 

#### Results
The ALK stock performed the best. In second place, was UAL. In third place was LUV.

#### Contact and Further Information
This project was completed by Katherine Lopez
