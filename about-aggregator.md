---
cover: .gitbook/assets/cover-gitbook2.jpg
coverY: 0
---

# About Aggregator

Hera Aggregator is a protocol that aims to provide the best swap return by scanning multiple liquidity provider markets. It uses trade splitting and multi-hop features to find the best route.

Sometimes it interacts directly with a single AMM to find the best route. Depending on need, it operates on multiple AMMs. It creates new paths by dividing it according to the input amount. Each road creates the best route independently of each other, therefore, the maximum output amount is made. In other words, both maximum income is obtained and a balance is created in the pools.

![](.gitbook/assets/overview-friendly.jpg)

Hera has an artificial intelligence powered off-chain calculation program that creates routes. The AI makes 252,000+ calculation attempts on each query. It finds all liquidity pools and creates routes without over draft scenarios.

It compiles all routes and approves them in a single transaction safely and efficiently.



### multi-hop routes. <img src=".gitbook/assets/multi.png" alt="" data-size="line">

Hera connects all DEX markets and AMM pools no matter the provider and finds all direct and 2-hop to 5-hop routes between any two tokens on integrated networks. There can be up to 5 tokens included in a transaction path. So, it supports a maximum of 5-hop currently.

Not only does Hera Aggregator compare the prices between markets on different DEXes but often the best priced routes are not direct markets. Instead, Hera may finds the best price by routing through an intermediary token, e.g. "X>Z>Q>Y" instead of "X>Y". This may be due to price inefficiencies and/or volatility in the various markets that Hera Aggregator routes through.

Here are some key features for how Hera Aggregator discovers the best priced trades.



### trade splitting. <img src=".gitbook/assets/split.png" alt="" data-size="line">

Hera Aggregator will split your trade into smaller trade sizes. For example, if you want to make a 100 USDC-ETH trade, it may distribute your trade into a 30 USDC-ETH trade on AMM1 and a 70 USDC-ETH trade on AMM2.

The % distribution of the trades is dynamically determined to give you the best price. Trade splitting helps get better prices for large size trades and trades with tokens where there is shallow liquidity spread out across a number of DEXes.



### other key features of Hera <img src=".gitbook/assets/best.png" alt="" data-size="line">

**Automatically lists new tokens**

The number of new tokens being added is increasing at an ever faster pace. This means you can be assured that you'll be able to trade new tokens as they launch on integrated networks.

**Lists new markets rapidly**

The number of markets and liquidity pools that are launching is also increasing. So, Hera instantly picks up any market or pool for any of the DEXes it currently aggregates. This ensures that Hera always has the latest liquidity for any token that is listed as soon as it is available.

**Swap in a single transaction**

Hera has worked to optimize its swap aggregation so that it all fits with the transaction limits so that swapping can be done in one transaction. This is important to handle cases where the price for the token you are buying has changed and no longer fits your slippage limit. If Hera Aggregator cannot make the trade with your slippage limit, it rollsback the transaction and return an error.
