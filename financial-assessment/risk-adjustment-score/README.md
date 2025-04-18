# Risk Adjustment Score

The "Risk Adjustment Score" is a composite metric that takes into account multiple factors influencing the risk profile of a token, with each factor weighted based on its relative importance. The formula aggregates these various scores to provide a comprehensive assessment of the token’s overall risk. Here's how it works:

Risk Adjustment Score= B\*Y+C\*X+D\*W+E\*V+F\*U+G\*T

Where

A is the Ease of Liquidation Score

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

* **Holding Time Score (Z)**: 0.15
* **Volatility Score (Y)**: 0.20
* **Balance Score (X)**: 0.10
* **All-time Risk Score (W)**: 0.05
* **Time Since All Time Score (V)**: 0.05
* **Time Since All Time High Score (U)**: 0.05
* **Time Since All Time Low Score (T)**: 0.05
* **Average Duration Score (S)**: 0.10
* **Gainers Score (R)**: 0.10
* **Liquidity Score (Q)**: 0.25





