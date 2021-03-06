# Python Crypto Assignment 2: Cryptocurrency Arbitrage Opportunities and Finding Mismatched Prices 
## What is 'Arbitrage'</b>
<p>Arbitrage is the simultaneous purchase and sale of an asset to profit from a difference in the price. It is a trade that profits by exploiting the price differencesof identical or similar financial instruments on different markets or in different forms. Arbitrage exists as a result of market inefficiencies. </p>
<img src="images/p1.png">
## BREAKING DOWN 'Arbitrage' 
<p> Arbitrage provides a mechanism to ensure prices do not deviate substantially from fair value for long periods of time. With advancements in technology, it has become extremely difficult to profit from pricing errors in the market. Many traders have computerized trading systems set to monitor fluctuations in similar financial instruments. Any inefficient pricing setups are usually acted upon quickly, and the opportunity is often eliminated in a matter of seconds. Arbitrageis a necessary force in the financial marketplace. 

## A Simple Arbitrage Example 
<p>As a simple example of arbitrage, consider the following. The stock of Company X is trading at $20 on the New York Stock Exchange (NYSE) while, at the same moment, it is trading for $20.05 on the London Stock Exchange (LSE). A trader can buy the stock on the NYSE and immediately sell the same shares on the LSE, earning a profit of 5 cents per share. The trader could continue to exploit thisarbitrage until the specialists on the NYSE run out of inventory of Company X'sstock, or until the specialists on the NYSE or LSE adjust their prices to wipe out the opportunity. </p>
## Step 1: Create a Super Simple Cryptocurrency Arbitrage Program for Finding Mismatched Prices in Python 

Take a look at the following article and replicate this functionality in Python: https://medium.com/spreadstreet/a-super-simple-cryptocurrency-arbitrage-spreadsheet-for-finding-mismatched-prices-a6e8b12dd8b0


## A Complicated Arbitrage Example 

Though this is not the most complicated arbitrage strategy in use, this example of triangular arbitrage is more difficult than the above example. In triangular arbitrage, a crypto trader converts one cryptocurrency to another at one crypto exchange, converts that second currency to another at a second exchange, and finally converts the third currency back to the original at a third exchange. The same exchange would have the information efficiency to ensure all of its currency rates were aligned, requiring the use of different crypto exchanges for this strategy. For example lets look into example for fiat currency, assume you begin with $2 million. You see that at three different exchanges the following currency exchange rates are immediately available: Exchange 1: Euros/USD = 0.894 Exchange 2: Euros/British pound = 1.276 Exchange 3: USD/British pound = 1.432 First, you would convert the $2 million to euros at the 0.894 rate, giving you 1,788,000 euros. Next, you would take the 1,788,000 euros and convert them to pounds at the 1.276 rate, giving you 1,401,254 pounds. Next, you would take the pounds and convert them back to U.S. dollars at the 1.432 rate, giving you $2,006,596. Your total risk-free arbitrage profit would be $6,596

## Step 2: Create a Python Program, which identifies for you different opportunities to do triangular arbitrage in the crypto currency exchanges as shown in the above example.