# Time Weighted Dollar-Cost Averaging

Time-Weighted Dollar-Cost Averaging (DCA) is used when the amount obtained from a liquidation event exceeds what can be profitably sold across all available liquidity pools and chains at once. In this scenario, selling the entire position immediately would cause excessive slippage and value loss, so DCA is employed to distribute sales over time and multiple transactions. This approach reduces market impact but introduces new risks, as it depends on continued buy pressure and arbitrage to maintain profitability.&#x20;

### Length of DCA

The DCA period should be carefully chosen based on several factors:

* Total Liquidity: The sum of liquidity available across all pools and chains. Higher liquidity allows for faster DCA without excessive slippage.
* Trading Volume: The average daily trading volume for the token. Higher volume supports larger DCA increments, as the market can absorb more tokens without significant price movement.
* Risk Premium: The risk that market conditions will worsen during the DCA period. If there’s a high risk of further sell pressure or negative news, the DCA schedule should be accelerated. If risk is low, the period can be extended for more gradual selling.
* Fee per transaction- A .1% of trade is often applied as a fee for the DCA tool, however this varies for what is used. If DCAing over a long period and amount of trades this can add up quickly- 10 trades can add up quickly to 1%.&#x20;

### Dynamic Adjustments

* Monitoring: Market conditions should be continuously monitored during the DCA period. If liquidity or trading volume drops, or if sell pressure increases, the DCA schedule may need to be adjusted—either accelerating sales to reduce risk exposure or pausing to wait for better conditions.
* Hybrid Approaches: Sometimes a hybrid approach is used, combining initial bulk sales with DCA for the remainder, or switching between strategies as market conditions change.
