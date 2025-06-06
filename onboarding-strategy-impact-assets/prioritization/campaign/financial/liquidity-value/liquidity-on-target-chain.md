# Liquidity on Target Chain

The target chain is defined as the chain on which we have setup our smart contracts for the stablecoin protocol. The amount of liquidity a token has on the target chain is essential when it is considered for use as collateral. A token can be bridged from other chains to the target chain, however already having liquidity on the target chain boosts the priority at which a potential asset is considered for use as collateral.&#x20;

In order to encourage an asset to migrate liquidity to a target chain, we may accept the asset with a very low max collateral amount at first and dynamically adjust the collateral amount as more liquidity is added to the target chain.&#x20;

The target chain in which we have our contracts deployed is specified in the dev documents under contracts.&#x20;

