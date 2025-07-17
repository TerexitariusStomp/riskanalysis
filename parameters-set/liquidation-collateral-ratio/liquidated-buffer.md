# Liquidated Buffer

Once an asset is liquidated, the difference between not having any further overcollateralization (no overcollateralization is 1 USD : 1 USD) and the liquidation buffer, is the liquidated buffer. In order to not accrue bad debt the assets need to be liquidated within that buffer.  The liquidated buffer is designed to protect the protocol from bad debt. It also ensures liquidators can operate profitably even with market slippage.

This can be calculated as follows

$$
L=B−P−T
$$

$$
L>M
$$

Where&#x20;

**Liquidation buffer** = B

**Liquidation Penalty** = P

**Liquidation Tip** = T

**Liquidated Buffer** = L

Maximum Slippage that Could Occur From Liquidation = M
