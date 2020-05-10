## Welcome to bot grid trading

I started this guide as personal reference and for my wife whom I have been trying to teach the art of grid trading. I have been trading and hodling crypto currency since 2017 but only tried bot grid trading in 2020.

All the content here are from my personal experience doing bot grid trading and should not be taken as a financial advice. Use your own due diligence when using the content here. Your money, your responsibility. 

## What is bot grid trading? 

There are two terms here **bot** and **grid trading**. A bot is a tool that performs task autonomously. Here we will use a bot to automate the placing of order in grid trading. To effectively describe grid trading I would need to define some ideas and technique first. 

### But low, sell high

This is perhaps the most basic and oldest principle in trading. Buy an entity at a price and sell it higher, the difference from the buy and sell is the gain. So if you buy 1 BTC at $8,000 and sell it later for $10,000, then your gain is $2,000. 

The problem with this (all-in) technique is when the sell price you set is not reached. So for our example above, you won't be able to sell if the price only reached $9,000. You'll have to wait a little bit longer if the price went down again after reaching $9,000. What traders do is do ladder tradding

### Ladder trading

In this technique, instead of selling all of the BTC at $10,000. You can divide it and sell it on different price levels or the ladder. That way you still gain even if the price didn't reach $10,000. So for our previous example, let's say you decide to sell in 4 equal amount (0.25) 

| Sell Price    | Quantity      | Gain  |
| ------------: |--------------:| -----:|
| $8,500        | 0.25          | $125  |
| $9,000        | 0.25          | $250  |
| $9,500        | 0.25          | $375  |
| $10,000       | 0.25          | $500  |

The downside of ladder selling technique is you gain less. Instead of gaining $2,000 you only gained $1,250 with ladder trading. 

The problem with ladder technique is if upon buying the price went down. You need to wait again for the price to go up before you can trade. 

### Grid trading

Grid trading have the same concept as ladder selling method. Instead of just having a sell order, you also have a buy order. So if the price went down below $8,000 you can still trade and make profit.

So for our previous example (current BTC price is at $8,000) we can put 2 buy orders and 2 sell orders. 

|Order Type    | Sell Price    | Quantity      | Gain  | Investment |
|:-------------| ------------: |--------------:| -----:|-----------:|
|BUY           | $7,000        | 0.25          | N/A   | $1,750     |
|BUY           | $7,500        | 0.25          | N/A   | $1,875     |
|SELL          | $8,500        | 0.25          | $125  | $2,000     |
|SELL          | $9,000        | 0.25          | $250  | $2,000     |

Now if BTC price went down to $7,500, the buy order will be filled and it will be placed as a sell order at $8,000 (with gain of $125 ig).

|Order Type    | Sell Price    | Quantity      | Gain     | Investment |
|:-------------| ------------: |--------------:| -----:   |-----------:|
|BUY           | $7,000        | 0.25          | N/A      | $1,750     |
|**SELL**      | $8,000        | 0.25          | **$125** | $1,875     |
|SELL          | $8,500        | 0.25          | $125     | $2,000     |
|SELL          | $9,000        | 0.25          | $250     | $2,000     |

Instead of spending $8,000 to buy BTC you will only spend $4,000 to buy 0.5 BTC. Total investment is also smaller with grid trading at $7,625 only instead of $8,000.

### Bot trading

## Managing Risk
- Goal is not to earn but to preserve capital
- Entry Point - Bear market, 90 day all time low. Patience
- Dollar Cost Averaging, 1 grid per day
- 50/50 invest 50% of your portfolio only
- Watch the news

## Choosing coin
- Volume
- Listing delisting, ETHBEAR and ETHBULL case
- Choose coin you don't mind to HODL
- Start with ONE Coin
- +/- 3% average change per day
 
## Grid Set-up
- Exchange and bot app
- Sell One Grid Higher - Realized Gain
- Forever 21, 1% set-up
- Trading Fee
- Minimum grid investment
- Goal Setting, $1 gain per tick

 ## Other topics
- Review Exchanges for Bot Trading
- Review App that supports Bot Trading
- Coins/Token to bot trade
