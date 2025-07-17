# Single Pool Liquidation

### Single Pool Instantaneous Liquidation Strategy

### Key Challenges

Selling all assets from a liquidation in one transaction can cause significant slippage and lead to losses. It’s important to calculate how much can be sold instantly versus how much should be distributed over time. Flash loan liquidations are only suitable for scenarios where the entire position can be liquidated instantly. Flash loans happen before a Dutch Auction would occur.&#x20;

### Target Pool Liquidity Analysis

### Pool Structure and Depth

The target pool is the deepest liquidity pool for the liquidated token. Initially, this is likely to be paired with USDC or WETH, but the goal is to use AZUSD as the primary pair. If it is not an AZUSD pair then the paired token (example USDC or WETH) would need to be sold to get AZUSD and pay back the amount of debt owed. This incurs a fee as well that should be included in this calculation. In a balanced pool, the assets are split 50:50 by value, so half the pool is available for liquidation.

### Mathematical Framework

### Total Instantaneous Liquidation Capacity

The maximum amount that can be sold instantly is calculated as:

Total Amount Able to Be Sold Instantaneously = Target Pool Liquidity × Maximum tolerance

This formula accounts for:

* Available liquidity in the pool
* Acceptable slippage
* The relationship between trade size and market impact

It is advantageous to sell as much as possible instantaneously as it mitigates risk variables of selling over time.&#x20;

\
