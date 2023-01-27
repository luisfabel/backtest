# backtest
Details

Short Description

This strategy aims to compare the difference betweewn holding a stock (buy and hold) for a ceratin period or trading it using the RSI indicator (Model Result). 

Specifics:
Buy and Hold: Asumes that you buy 2 stocks and the begining of the period.
Model Result: Asumes that you will buy 1 stock at the begining of the period and buy 1 more (up to 2) or sell (1 at the time) through the period based on the RSI.

Model Speficics:
Cannot hold more than 2 stocks at any time.
Buy Order signal is when RSI is under X (28 is the default)
Sell Order: it consists in two parts:
            1. Get a "sell signal" because RSI is over X (Default is 70)
            2. The stock falls from its highest peak, 25% of its standard deviation

Modifiables:
- Stocks to analyze
- RSI
- Period of analysis
