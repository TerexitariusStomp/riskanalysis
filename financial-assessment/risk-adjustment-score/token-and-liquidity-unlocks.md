# Token and Liquidity Unlocks

The Token Unlock Risk Score is determined through a combination of factors related to token unlock schedules and liquidity:

Unlock Risk Score = (1-F) x (1-S) x D X (1-C/U) x L x B

Where

F is the Frequency of unlocks&#x20;

S is the Size of unlocks&#x20;

D is the Distribution breadth (inverse of the number of people involved)&#x20;

U is the Unlock to circulating supply percentage&#x20;

C is the Circulating supply&#x20;

L is the Amount of Locked liquidity&#x20;

B is the Amount of Burned liquidity

Higher Unlock Risk Score (closer to 1): Indicates that the token has a less risky unlock schedule, with less frequent, smaller unlocks distributed to more people, and a lower percentage of tokens being unlocked relative to the circulating supply.&#x20;

Lower Unlock Risk Score (closer to 1): Indicates that the token has a more risky unlock schedule, with more frequent, bigger unlocks distributed to fewer people, and a higher percentage of tokens being unlocked relative to the circulating supply.&#x20;

