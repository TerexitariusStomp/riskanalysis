# Liquidation Penalty

The Liquidation Penalty functions as both a deterrent against excessive leverage and a mechanism to ensure sufficient collateral recovery during liquidation events. Azos currently applies a uniform 5% penalty across all collateral types.&#x20;

The 5% penalty represents a significant cost for borrowers who allow their positions to reach liquidation. This encourages proactive position management and collateral addition before reaching critical thresholds. The penalty is immediately applied to the debt amount, meaning users lose this percentage regardless of how quickly liquidation occurs. This penalty is applied to the assets liquidated, however it could also be charged to the user that gets liquidated the next time they try to open a SAFE.&#x20;

\
