
#Bitcoin Investment Analysis – Skill vs. Gamble

1)Problem Statement: 
Analysing why some cryptocurrencies succeed while others fail. The goal is to identify patterns, trends, and strategies that help investors make informed decisions rather than gamble.

2)Objective:
1)Understand why some cryptos succeed while others fail.
2)Develop skills to analyse Bitcoin price movements.
3)Use data-driven strategies to maximize wealth.

3)Data Description:
	The dataset included: Unix, Symbol, Date time 
	Open (O): The price of Bitcoin at the beginning of the time period.
	High (H): The highest price Bitcoin reached during the time period.
	Low (L): The lowest price Bitcoin reached during the time period.
	Close (C): The price of Bitcoin at the end of the time period.
	Volume (BTC): The total number of Bitcoin traded during the time period.
	Volume (USD): The total value of all Bitcoin traded during the time period, converted into US dollars.
	USD: Represents values in US dollars.
	BTC: Represents values in Bitcoin.

4)Tools & Techniques:
•	Programming Language: Python
•	Libraries: Pandas, NumPy, Matplotlib, Seaborn
•	Techniques: Data Cleaning, Exploratory Data Analysis (EDA), Data Visualization, Trend Analysis, Pricing Insights
5) Project Workflow :
Step 1: Import Necessary libraries and Load the Dataset 
Step 2: Data Cleaning and Preprocessing
Step 3: Exploratory Data Analysis (EDA)
Step 4: Data visualization
Step 5: Insights and Recommendations
6)Data Visualization :
	Visualization of open, high, low ,close price trends:
•	The chart represents Bitcoin price trends using Open, High, Low, and Close (OHLC) values over a time period.
•	The x-axis represents dates and times.
•	The y-axis represents Bitcoin price in USD.
•	A legend in the top-right corner identifies the different lines.
•	The Bitcoin price declines sharply around the middle of the graph, indicating a significant price drop.
•	After the drop, the price appears to stabilize and start rising again.
•	The High and Low prices closely follow each other, showing price fluctuations within the given period.
•	The Open and Close prices are also close to each other, indicating that Bitcoin didn’t have extreme volatility after the big drop.
•	The sharp price decline could be due to market news, a crash, or liquidation events.
•	The recovery after the drop might indicate buyers entering the market, pushing the price back up.
•	This will help us identify long-term trends and volatility.

	Bitcoin Price Trend Over Time:
•	This graph represents the Bitcoin Price Trend Over Time using a line plot.
•	X-axis: Date & Time
•	Y-axis: Bitcoin price in USD
•	Orange Line: Bitcoin's closing price over time
•	 Sudden price drops & jumps – Indicates sharp fluctuations, possibly due to market events or missing data points.
•	 Flat segments – Suggests periods with little to no change in price.
•	Gaps in the line – Could be caused by missing data, incorrect indexing, or market inactivity.

	Bitcoin Daily Returns:
•	This graph represents Bitcoin Daily Returns over time.
•	X-axis: Date & Time
•	Y-axis: Daily Return (percentage change in closing price)
•	Blue Line: Daily percentage change in Bitcoin's price
•	Fluctuations in returns – Indicates Bitcoin's price volatility.
•	Some large spikes – Suggests sudden price movements, possibly due to market events.
•	Negative returns – Represent periods where Bitcoin's price decreased.

	Moving Averages for Buy/Sell Signals
•	The graph Represents Moving Averages for Buy/Sell Signals
•	BTC Close Price - orange
•	50-Day SMA - Blue
•	200-Day SMA - Red
•	Buy Signal 📈 when SMA_50 crosses above SMA_200
•	Sell Signal 📉 when SMA_50 crosses below SMA_200

	Investment Strategy performance
•	The graph Represents Investment Strategy performance
•	Buy& Hold- Orange
•	SMA Strategy -Blue
•	If Strategy Return > Buy & Hold, our strategy is profitable.
•	If not, we need to optimize buy/sell signals.

7) Insights& Recommendations :

	Bitcoin is volatile – Prices fluctuate heavily, leading to high risk & high reward.
	Moving Averages help identify trends – Useful for creating trading strategies.
	Investment Strategies matter – Simply "Holding" isn’t always the best strategy; active trading can increase profits.
	Bitcoin is volatile – High risk, high reward.
	Moving Averages identify trends – Useful for trading strategies.
	Simple strategies can improve profits – Instead of blindly holding.
