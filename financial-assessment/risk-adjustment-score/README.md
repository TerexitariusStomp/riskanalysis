# Risk Adjustment Score

The "Risk Adjustment Score" is a composite metric that takes into account multiple factors influencing the risk profile of a token, with each factor weighted based on its relative importance. The formula aggregates these various scores to provide a comprehensive assessment of the token’s overall risk. Here's how it works:

Risk Adjustment Score= B\*Y+C\*X+D\*W+E\*V+F\*U+G\*T

Where

B is the Ease of Liquidation Score

Y is the Weighting of B

C is the Supply Distribution Score

X is the Weighting of C

D is the All-time Risk Score

W is the Weighting of D

E is the Time Since All Time Score

V is the Weighting of E

F is the Intraday Volatiliity&#x20;

U is the Weighting of F

G is the Volatility Score

T is the Weighting of G



**Before calculations the scores of each assessment methodology are normalized (assessment methodology example being ease of liquidation, normalized between 1 (best score) and 0 (worst score)).**&#x20;

**A higher overall score** (from summing the weighted variables) indicates that the token is more suitable as collateral, while a **lower overall score** suggests higher risk and less suitability for collateral purposes



Current Weights

Ease of Liquidation Score Y- 25%

Supply Distribution Score X-  20%

All-time Risk Score W-  10%

Time Since All Time Score V- 10%

&#x20;Intraday Volatiliity U- 15%

Volatility Score T- 20%



Justification of Weights-&#x20;

Y- Directly impacts slippage risk and exchange stability. Deep liquidity pools (low volume-to-liquidity ratios) prevent market manipulation.&#x20;

X- Measures dilution risk from unlocked tokens. Negative values signal future price shocks, requiring higher collateral buffers.

W- Historical price extremes indicate long-term speculative behavior but are less predictive of near-term risks.

V- Recent proximity to ATH/ATL suggests momentum trends but has limited bearing on structural liquidity.

U- 24h price range reflects immediate market sentiment and short-term liquidation risks during margin calls

T- Multi-timeframe volatility (1h to 90d) captures systemic price instability risks, critical for collateral backing stablecoins



