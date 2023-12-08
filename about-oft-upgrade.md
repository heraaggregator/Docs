---
cover: .gitbook/assets/cover-gitbook-token.jpg
coverY: 0
---

# About OFT Upgrade

This update covers three key features. First off, we'll be deploying the OFT Token. Don't worry, Metis' existing token address and liquidity won't change. However, we're introducing the Hera Token, set to deploy on Ethereum and subsequent chains, rocking a single contract address. After the Ethereum expansion, get ready for a HERA/USDC pool on Uniswap v3. All contract addresses will be revealed post-announcement; stick to the official details to avoid any confusion.

Now, let's talk about the OFT burn/mint feature. It's designed to expand an existing token, and here's the scoop. When the Hera Token hits Ethereum, the supply starts at zero and mints Hera proportional to the tokens bridged from Metis. On Metis, those tokens chill in a Proxy contract. Bridge them to Ethereum, and voila! Tokens burn on the OFT contract, Metis Proxy reimburses. It's a zero-accounting magic trick.

The bridge and inter-chain transactions vary, taking 15s to 4m, depending on each chain's quirks. We'll keep an eye on it and roll updates as needed.

Now, let's talk omnichain staking, the complex beast. No matter which chain you transact from, tokens funnel straight to the Metis chain's contract. Staking from Metis? Direct drop into the pool. Other chains? After bridging. It's an omni-staking pool, serving any future chain expansions. It operates independently across chains. We've got four main functions: stake, unstake, claim, and compound. All real-time for Metis, variable for OFT chains.

***

**Got questions?** Here are some FAQs 👇

* If your tokens are on Metis and you want to stake, no need to bridge. Start staking directly from the Portal. OFT chains are a secondary option.
* We've crafted a fresh portal for bridge and staking. Ditch the old frontend for the new portal. If you've staked in old pools, unstake there and hop on the new portal. We'll keep the old frontend alive for a bit.
* After the bridge cooldown, OFT tokens will mint to your wallet from the 0x000...00 address. No need for a secondary claim or mint action.
* Initial liquidity on Uniswap in Ethereum. Balanced liquidity shift from Metis pools—HERA and USDC—to Ethereum. Gradually optimized.
* Post-OFT upgrade, you can still enjoy Hera features on Metis without using any bridges.
* Portal functions on Ethereum may see high fees at times. For gas savings, it's smarter to use these features on Metis.
* V3 update pending, so Hera Dex Aggregator isn't available for Hera trades on Ethereum. Use Uniswap or other swap protocols for now.
