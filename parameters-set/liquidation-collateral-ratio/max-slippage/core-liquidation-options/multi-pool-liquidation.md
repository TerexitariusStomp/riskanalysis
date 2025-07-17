# Multi Pool Liquidation

In a multi pool instantaneous liquidation event. All pools on the target chain are used as liquidity sources, for example both the USDC and WETH pools. The same calculation applies as the single pool liquidation, however with one added consideration.

## Compounding Slippage

If a pool is paired with another token that is a token that does not have deep liquidity (deep liquidity pools for example are USDC or Weth while tokens without deep liquidity are tokens that are often tokens that are not widely used). Then it is more exposed to compound slippage. Every token traded for the asset liquidated adds to the overall slippage.&#x20;

\
