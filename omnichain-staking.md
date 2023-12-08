---
cover: .gitbook/assets/cover-gitbook-token.jpg
coverY: 0
---

# 🆕 Omnichain Staking

Introducing the omni-chain Hera Staking Portal!&#x20;

The $HERA staking model has now completely transformed and can be used independently across networks. With Hera Token's OFT upgrade, its dependency on specific chains has been reduced, creating a model that can expand to all networks. If Hera Token is deployed to a new chain, staking will be available shortly.

The new staking model is building on LayerZero, and the interchain messenger protocol is working seamlessly. Like OFT contracts, the staking protocol is distributed and managed from the Metis chain.

Function definitions and details:

* **Stake:** You can stake your Hera Tokens on one of the active chains.
* **Unstake:** You can withdraw your assets from the staking pool.
* **Claim:** Use the claim function to transfer your staking rewards to your wallet.
* **Compound:** It's a quick solution to claim and restake your staking rewards.
* Some more fetures coming soon ...

**Notice:**&#x20;

Metis is defined as the main chain for staking pools. So, if you stake Hera Tokens on other networks, the tokens will be moved to the Metis network after communicating with proxy and bridge contracts. During this process, gas/tx fees and transaction times may vary due to the involvement of bridge contracts. The same considerations apply to unstaking, claiming, and compounding. Therefore, if you want to save time and fees, you can continue to use the staking portal on Metis.

You will use the existing token for staking on Metis, while for new networks introduced with the OFT expansion, tokens with ownership of the OFT token contract will be valid.

***

#### Omnichain Staking Contracts

<table><thead><tr><th width="326">Name</th><th>Address</th></tr></thead><tbody><tr><td>HeraStakingProxy</td><td>#</td></tr><tr><td>HeraStakingLocal</td><td>#</td></tr></tbody></table>



**Note:** The deployment phase has not been completed yet.
