# Start2Impact - Python exercize - Trading bot

Exercise to practice with the coinmarketcap.com APIs:
The trading bot checks every 10 minutes if more than 4 currencies have increased in price by more than 3% in the last hour. If so, it open a buy order for the currency that has increased the most.
If the purchased currency drops more than 1% in the last hour, the bot close the order by selling the currency.
Only one order can be opened at a time.
