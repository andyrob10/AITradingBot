# AITradingBot
AI Trading Bot
This is a small basic program for doing analysis of the US financial markets. It compares discounted cashflows share price against real time trading prices. If the stock is under or over valued from the entire market it will filter the top 5 most under valued (buys) and the top 5 most over valued (short) at any given time during a trading day. 

The DCF share price's are pulled via an API with financial modelling prep. They use linear regression to work out the projected share price. The filtering process does not look at the middle market only the shares where large deviations exist between DCF and actual close prices.

