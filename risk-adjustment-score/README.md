# Risk Adjustment Score

The "Risk Adjustment Score" is a composite metric that takes into account multiple factors influencing the risk profile of a token, with each factor weighted based on its relative importance. The formula aggregates these various scores to provide a comprehensive assessment of the token’s overall risk. Here's how it works:

Risk Adjustment Score= A\*Z+B\*Y+C\*X+D\*W+E\*V+F\*U+G\*T+H\*S+I\*R+J\*Q

Where

A is the Holding Time Score

Z is the Weighting of A

B is the Volatility Score

Y is the Weighting of B

C is the Balance Score

X is the Weighting of C

D is the All-time Risk Score

W is the Weighting of D

E is the Time Since All Time Score

V is the Weighting of E

F is the Time Since All Time High Score

U is the Weighting of F

G is the Time Since All Time Low Score

T is the Weighting of G

H is the Average Duration Score

S is the Weighting of H

I is the Gainers Score

R is the Weighting of I

J is the Liquidity Score

Q is the Weighting of J



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

#### Rationale Summary:

* **Liquidity** and **volatility** are prioritized due to their direct impact on market stability and ease of trading. These factors are given the highest weights because they provide the clearest indicators of a token's risk when used as collateral.
* **Holding time** and **average duration** are also important as they suggest how speculative or stable the token's holder base is, so they are moderately weighted.
* **Balance**, **gainers**, and **time-related metrics** are still relevant, but they offer less immediate impact compared to liquidity and volatility, so they receive smaller weights.



