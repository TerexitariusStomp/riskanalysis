# Bridged Multi Pool Liquidation

In a bridged multi pool instantaneous selling event. All pools on all chains are used as liquidity sources, for example both the USDC and WETH pools in both Base and Eth. The same calculation applies as the single pool liquidation, however with two added considerations. Flash loans can still be used in this method.

## Compounding Slippage

If a pool is paired with another token that is a token that does not have deep liquidity (deep liquidity pools for example are USDC or Weth while tokens without deep liquidity are tokens that are often tokens that are not widely used). Then it is more exposed to compound slippage. Every token traded for the asset liquidated adds to the overall slippage. As well as every time tokens are bridged to and from target blockchain.

\


## Bridge Fees

Bridging to and from the liquidity pool occurs both as a time risk as well as a bridge fee.&#x20;

\


The time required to move from one chain to another might be enough to have the liquidity on the target chain removed or sell event(s) to occur. Once traded on the other chain the value needs to be moved back to the target chain to repay debt.

\
