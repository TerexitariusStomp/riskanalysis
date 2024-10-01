# Liquidity Score

The "Liquidity Score" is a metric designed to assess the liquidity of a token by comparing its 24-hour trading volume to its total liquidity. This score helps gauge how easily the token can be bought or sold without affecting its price significantly, which is important for evaluating the token's suitability as collateral.

The Liquidity Score is determined through the 24 hour trading volume divided by the total liquidity&#x20;

Liquidity score= 1−(A/B)

Where&#x20;

A is the 24 Hour trading volume&#x20;

B is the Total Liquidity&#x20;

* Normalized between 0 and 1, where a lower ratio of volume to market cap indicates higher liquidity change thus lower risk.

**Higher Liquidity Score (closer to 1)**: Indicates that the token has higher liquidity relative to its trading volume. This suggests that the token is more stable and easier to trade without impacting the price, which is favorable for collateral use.

**Lower Liquidity Score (closer to 0)**: Indicates that the trading volume is high relative to the available liquidity, which could suggest potential price volatility and a higher risk of slippage. This makes the token less ideal for use as collateral.
