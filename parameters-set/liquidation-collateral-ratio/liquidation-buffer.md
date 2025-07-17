# Safety Collateral Calculations

The Safety Collatearl Ratio is determined through the volatility of the asset as well as the financial risk score.&#x20;

Let's examine the initial collateral assets of Azos.&#x20;

Stable Asssets

HLSp and USDGLO have minimal changes as they are designed to be pegged to $1 USD. USDGLO has a negative % change for 60Days which says it has changed roughly -7% since what it was 60 days ago. With further people using it through adoption, this % change was not included in the estimation of the liquidation buffer. Instead a standard 4% change was set. Both of these assets are not looked at as very risky assets as long as their redemption pools are maintained, maintaining the capability of redeeming them for $1 USD.&#x20;

Volatile Assets

WETH and KLIMA are both volatile assets. Klima has shown a -12% drop in value over 60 days. This means that if the vault were to have been created 60 days ago, a maximum amount of debt taken from that vault and no maintenance was done on the vault; it would be about 18% away from the liquidation ratio. Both Klima and Ethereum are risky assets, with Klima receiving a financial risk score twice as risky as Ethereum (see financial assessment for more details). As such a standard 30% buffer was placed on both assets.&#x20;

| Token  | HourNegative | DayNegative | WeekNegative | 30daysNegative | 60DaysNegative |
| ------ | ------------ | ----------- | ------------ | -------------- | -------------- |
| KLIMA  | -0.20353871  | -0.99852692 | 0            | 0              | -12.28495795   |
| HLSp   | 0            | 0           | 0            | 0              | 0              |
| USDGLO | -0.64125759  | 0           | 0            | 0              | -7.30180237    |
| Ether  | -0.64276872  | 0           | 0            | 0              | 0              |

