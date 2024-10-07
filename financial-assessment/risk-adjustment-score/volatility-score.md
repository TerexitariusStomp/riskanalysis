# Volatility Score

The "Volatility Score" is designed to measure how much the price of a token fluctuates over various time periods. It combines the percentage price changes over several time frames, giving an average measure of volatility that is then scaled to a usable range. Here’s how it works:

**Volatilty Score is Composed Of The Price Change Over Different Time Periods**

**Volatility Score= (A+B+C+D+E/5)\*.01**

**Where**&#x20;

**A is 24 Hours**

**B is 1 week**

**C is 30 Days**

**D is 60 Days**&#x20;

**E is 90 Days**

**.01 is Applied to Bring Percent Score into Decimal**

A higher Volatility Score indicates that the token's price fluctuates more dramatically, making it potentially less suitable as stablecoin collateral due to increased risk of price instability. Conversely, a lower score reflects more stable price behavior over time, which is generally more desirable for collateral backing a stablecoin.&#x20;

Negative scores indicate an overall decline in value, while positive indicate a rise in value. These are the most important attributes here.&#x20;
