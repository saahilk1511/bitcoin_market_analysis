# Bitcoin Market Analysis

# Context

Bitcoin is the longest-running and most well-known open-source peer-to-peer cryptocurrency. Launched in 2009 by its anonymous creator Satoshi Nakamoto, Bitcoin originally serves as a decentralized medium of digital exchange, with transactions verified and recorded in a public distributed ledger, also known as the blockchain. In doing so, a person transacting value across the Bitcoin network does so without needing an intermediary. 

Every transaction block contains a SHA-256 cryptographic hash of the previous transaction block. They are thus “chained” together, serving as an immutable record of all transactions that have ever occurred across its decentralized network. 

There can be only 21 million Bitcoin tokens. Many investors and analysts treat its underlying scarcity as similar to gold, a traditional safe-haven asset. Therefore, Bitcoin has grown from a financial experiment to a serious contender in the global hedging instrument space. That said, its demand as a financial instrument has boomed exponentially in its 12-year lifetime.

The report below includes historical Bitcoin market data at 1-min intervals for select cryptocurrency exchanges.


# Objective

To analyze and summarize Bitcoin price performance between January 2012 and December 2020 by studying its distribution of closing index, volume profile, and transaction data.


# Bitcoin Price Through the History

The virtual currency has had a volatile trading history since its creation in 2009. The first most notable price hike occurred during 2013 when the cost to purchase one Bitcoin reached $1,124 in November. 

Four years later, the cryptocurrency experienced a meteoric rise and reached record highs, with bids on some exchanges for single bitcoin touching circa $20,000 during the December 2017 session. 

However, the prices started tumbling in the months that followed. In the third quarter of 2020, there were around 18.5 million bitcoins in circulation worldwide, and the market capitalization of Bitcoin was approximately $200 billion.

Bitcoins trading is available across multiple cryptocurrency exchanges across the globe. Each exchange maintains a private market maker to reflect on Bitcoin’s ask and bid rate. Therefore, the bitcoin price tends to vary per the exchange it trades on. Meanwhile, some services, including Coindesk, curate the bitcoin price performances across all the exchanges to provide an average, unified bitcoin price.

![newplot](https://user-images.githubusercontent.com/77642698/122210360-8e5db980-ce73-11eb-9ae1-d2a7c4f4bdea.png)


# Volume Confirms Trends

The volume of bitcoin is the amount of market activity it experiences. In the case of extremely bullish and bearish price trends, one should notice spikes in Bitcoin’s trading volumes. A confirmed trend happens when the price moves with equal momentum as the volume.

The trading volume indicates how many bitcoins are being bought and sold on specific exchanges. High trading volumes are likely to drive more on-chain activity. For instance, when people deposit and withdraw funds, their activity gets recorded atop the Bitcoin blockchain. That said, the higher the Bitcoin transactional activity, the excessive are the volumes. 

It is also a good indicator of the general interest in the crypto market.

![newplot (1)](https://user-images.githubusercontent.com/77642698/122210384-961d5e00-ce73-11eb-9d7f-04d2f8ae7f2f.png)

![newplot (2)](https://user-images.githubusercontent.com/77642698/122210420-9f0e2f80-ce73-11eb-943d-0ef5b3bf40fa.png)


# Distribution of volume of bitcoin transactions and closing index

![newplot (3)](https://user-images.githubusercontent.com/77642698/122210455-aa615b00-ce73-11eb-85b4-4ac3a3ff4eef.png)

![newplot (4)](https://user-images.githubusercontent.com/77642698/122210456-aaf9f180-ce73-11eb-8d80-00cc88e1b9bc.png)

![newplot (5)](https://user-images.githubusercontent.com/77642698/122210457-aaf9f180-ce73-11eb-88ce-d7dc779dabc0.png)


# Correlations Between Variables

Correlation heatmap shows us that volume of corresponding currency has positive correlation with bitcoin prices, as expected. On the other volume of bitcoin naturally has a negative correlation with its own prices. The larger volume the bitcoin has, the less valuable it is.

Correlation between prices of bitcoin in different times is 1.0.

![newplot (6)](https://user-images.githubusercontent.com/77642698/122210486-b2b99600-ce73-11eb-8738-c526ba6fc934.png)


# Open vs Close

"Open" and "Close" prices of bitcoin will be nearly linear, because they have 1.0 correlation.

![newplot (7)](https://user-images.githubusercontent.com/77642698/122210500-b77e4a00-ce73-11eb-94b8-73c772cc5b2f.png)

# Central Limit Theorem

The Central Limit Theorem states that the sampling distribution of the sample means a normal distribution as the sample size gets larger — no matter what the shape of the population distribution. This fact holds especially true for sample sizes over 30.

The graphs below shows the sample means of 5000 random samples of the closing index of sample sizes 10, 20, 30, and 40 follow a normal distribution.

![newplot (8)](https://user-images.githubusercontent.com/77642698/122210524-bc42fe00-ce73-11eb-8388-06ce5123f3dd.png)


<img width="766" alt="Screen Shot 2021-06-16 at 7 28 16 AM" src="https://user-images.githubusercontent.com/77642698/122211217-7b97b480-ce74-11eb-8f93-6d8c29dcbc29.png">


# Price analysis using sampling techniques

Price analysis is the ongoing process of cryptocurrency traders and analysts finding patterns in the market to determine optimal trading strategies and gauge market sentiment.

Using various sampling methods, we will try to identify these trends and market sentiment by randomly selecting days and it's corresponding closing index between 2017-2020.


<img width="779" alt="Screen Shot 2021-06-16 at 7 29 15 AM" src="https://user-images.githubusercontent.com/77642698/122211301-94a06580-ce74-11eb-9bcc-430be0ad1a87.png">


## Observations

### Tenets of Dow Theory - Market Movements

In our technical market analysis using sampling methods, we focused on Bitcoin’s price action during randomly-chosen periods.

__Main Movement__ – The main movement is the major trend currently underway. This trend is going to encompass years of market activity. The main movement in the Bitcoin market is bullish if you look at its complete trading history.

![newplot (9)](https://user-images.githubusercontent.com/77642698/122210571-ca911a00-ce73-11eb-91d4-03de92c075a9.png)



__Medium Swing__ – A medium swing is a secondary market reaction. This reaction can last for up to three months. Medium swings include price retraces. A retrace is when Bitcoin’s market movement begins to return to its original state prior to the market activity.
We sampled 90 random days in the Bitcoin market from 2019 and curated closing rates that appeared similar to the original data set.  

<img width="764" alt="Screen Shot 2021-06-16 at 7 29 38 AM" src="https://user-images.githubusercontent.com/77642698/122211362-a550db80-ce74-11eb-950d-df3dae2d32e6.png">


![newplot (10)](https://user-images.githubusercontent.com/77642698/122210591-cf55ce00-ce73-11eb-8f90-3ea27f28756f.png)


# Tracking Bitcoin Price Performance Throughout 2017-2020

Price analysis is the ongoing process of cryptocurrency of finding patterns in the market  and gauge market sentiment.

The two main indicators that are sought after are whether or not the market is bullish with upward-trending price action or bearish with downward pressure on price.

Price analysis techniques vary and are often used in unison to provide as detailed a perspective of market conditions as possible. We can analyze a bitcoin’s volume in relation to its price or use candlestick charts to gauge market sentiment on a daily basis.

Ultimately these are means of spotting patterns at the micro and macro levels as indicators of overall industry growth.
 

### Closing Index

Number of days bitcoin traded above its yearly average

![newplot (11)](https://user-images.githubusercontent.com/77642698/122210657-ded51700-ce73-11eb-9ba3-d424f60477cf.png)


### Bitcoin Candlestick chart (2017-2020)

Candlestick charts provide us with everything we need to know to understand the current state of the market value of an asset. We can see the opening and closing prices, the daily high and low, and can decide on what time intervals we want this information displayed.

A green candlestick indicates that Bitcoin closed higher for the time period than its opening value. Anytime we see a red candle, it indicates there were some losses incurred by the asset. In this way, it’s easy to monitor market activity.

In most candles, we will notice there’s a body. Where the main body of the candle begins is the opening price for the day. If the candle is green, the opening price will be the bottom of the candle body. If the candle is red, the body’s top will let you know the opening price.

We can notice that the top or bottom always lines up with the proceeding candle in the chart. This alignment represents the close and opening of the next trading day. This time can varies depending on the trading interval you choose.

There are also small lines sticking out from the top and bottom of the candle. These lines are known as shadows. Shadows represent the high and low for the day. In this way, we can ascertain an incredible amount of information from a candlestick chart in seconds.

This data can then help us to make a timely investment decision.

![newplot (12)](https://user-images.githubusercontent.com/77642698/122210679-e4caf800-ce73-11eb-94d3-1694787924ba.png)


### Bitcoin Output Value

The average value and count of all transaction outputs.

![newplot (13)](https://user-images.githubusercontent.com/77642698/122210699-ea284280-ce73-11eb-8127-3cdb288b89c5.png)

![newplot (14)](https://user-images.githubusercontent.com/77642698/122210714-edbbc980-ce73-11eb-90c0-9e6e0c15d275.png)

![newplot (15)](https://user-images.githubusercontent.com/77642698/122210727-f0b6ba00-ce73-11eb-8051-f52196999534.png)


### Bitcoin Interday Returns and Volatility Index

Volatility is a measure of how much the price of a Bitcoin varies over time.

![newplot (16)](https://user-images.githubusercontent.com/77642698/122210751-f8765e80-ce73-11eb-92c3-08a2b5c98ecc.png)

<img width="768" alt="Screen Shot 2021-06-16 at 7 30 49 AM" src="https://user-images.githubusercontent.com/77642698/122211486-cadde500-ce74-11eb-8873-5feb10035db2.png">


![newplot (17)](https://user-images.githubusercontent.com/77642698/122210889-22c81c00-ce74-11eb-9938-a0e8c9358c30.png)



# Conclusion

Bitcoin's value has been historically quite volatile and will remain volatile for the foreseeable future. It is highly reactive to external trends and other market fluctuations.
Bitcoin has seen four significant corrections of the magnitude of 40% & above, with an average correction rate of 36%. The major market correction happened during its bull run in the year 2018. From Mid-March 2020 until 31st Dec 2020, Bitcoin has seen a price increase of 650% ($25032 in dollar value).


