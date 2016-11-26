# Wealthsimple Lightning Challenge

### Background
The stock market is a marketplace to trade securities. Securities, or stocks, are a way for people to own parts of a public company. For example, Facebook and Google have their stocks traded on stock markets in the USA.

There are a lot of day-traders on the stock market. Day traders try to leverage the day-to-day fluctuations of a stock and make a profit by buying low and selling high at the right times.

### Challenge
The challenge is to create an algorithmic trader. 

You will be given a test file with historical quotes of a certain stock or index fund. Using this data, you must output the trades you plan on making on each day.

### Details and Restrictions
When generating the trade for a given day, you may not use data from future days. For example, if you are generating the trade to be placed for July 2nd, 2014, you may not use the trading prices for July 3rd, 2014.

At any given time, you may not hold more than 1000 stocks.

If you hold any stocks at the end of the time period given, they will be sold at the last available market price.

### Input/Output
##### Input Format (From File, in.csv):
2012-09-01,142.45 # The price for the day is 142.45

2012-09-02,142.98

2012-09-05,144.11

2012-09-06,143.35

##### Output Format (To File, out.csv):
2012-09-01,500 # buy 500 stocks

2012-09-02,500

2012-09-05,-1000 # sell 1000 stocks

2012-09-06,0 # 0 means hold all stocks

### Winning
The winner will be the team that has the highest profit at the end of the data set given. 

The prize is a pair of Bose QC25 Headphones.


# Updates
You must handle any input errors, like malformed dates or empty prices. You can handle them any way you like, including skipping output for that day.
