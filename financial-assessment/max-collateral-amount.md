# Max Collateral Amount

To assess the maximum collateral amount we can accept in our protocol for an asset, we look at slippage of the asset. A tool to help us in doing this is [https://defillama.com/liquidity](https://defillama.com/liquidity). As we are overcollateralized, we can use the amount of overcollateralization as wiggle room for being able to buy bad debt and liquidate it on the open market. If we look at Klima to USDC on Base blockchain and set a max tolerance of slippage for 30% around $750,000 would be the maximum amount of collateral that we would be able to accept currently as of 4/18. As an asset is integrated into our protocol as a collateral its expected that variables related to slippage will improve and thus the maximum collateral amount will also rise (for example depth of liquidity of an asset).&#x20;



Liquidity on Target Chain

A tool like the above is good for assessing overall slippage, however we need to be specific to the chain on which liquidations are occuring.&#x20;



24 Hour Volume

To better understand if the max collateral amount is reasonable it can be compared to the 24 volume of the asset. &#x20;



Liquidity Secured

If there is a way to determine how much liquidity is secured (burned or locked) that can increase the confidence of the ability to exchange assets.&#x20;
