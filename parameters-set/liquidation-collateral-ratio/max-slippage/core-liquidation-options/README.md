# Core Liquidation Options

This framework outlines strategies for managing liquidated assets. The goal is to optimize asset sales to minimize value loss (minimizing slippage) and maximize profitability.

When a token is acquired through liquidation, there are strategies to sell the token. One way to sell the collateral assets is having agreements with the collateral assets as to buy back or redeeming it for another underlying value. For liquidation, Azos should try to use flash loans as much as possible to retain value within the organization. There are cases where after the Dutch auction has reached the maximum duration that Azos ends up with the asset at a maximum discounted rate. This likely leads to liquidations through the methods described below:

Redeem Asset

1. Redeem– For assets that are always redeemable for an underlying store of value.&#x20;

Flash Loan Capable

2. Single Pool Spot – Sell the entire position immediately on a single pool.&#x20;
3. Multi Pool Spot- Sell the entire position immediately through multiple pools.
4. Bridged Multi Pool Spot- Sell the entire position near immediately on all chains through multiple pools.

Not Flash Loan Capable

Time-Weighted Dollar-Cost Averaging (DCA) – Sell the position gradually over time.
