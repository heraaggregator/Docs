---
cover: .gitbook/assets/cover-gitbook-token.jpg
coverY: 0
---

# New - Staking Portal ✔

Introducing the omni-chain Hera Staking Portal!&#x20;

The $HERA staking model has now completely transformed and can be used independently across networks. With Hera Token's OFT upgrade, its dependency on specific chains has been reduced, creating a model that can expand to all networks. If Hera Token is deployed to a new chain, staking will be available shortly.

The new staking model is powered by LayerZero, and the interchain messenger protocol is working seamlessly. Like OFT contracts, the staking protocol is distributed and managed from the Metis chain.

Function definitions and details:

* **Stake:** You can stake your Hera Tokens on one of the active chains.
* **Unstake:** You can withdraw your assets from the staking pool.
* **Claim:** Use the claim function to transfer your staking rewards to your wallet.
* **Compound:** It's a quick solution to claim and restake your staking rewards.
* **Auto Compound:** Coming Soon (with extra rewards)

**Notice:** The Metis network is defined as the main chain for staking pools. So, if you stake Hera Tokens on other networks, the tokens will be moved to the Metis network after communicating with proxy and bridge contracts. During this process, gas/tx fees and transaction times may vary due to the involvement of bridge contracts. The same considerations apply to unstaking, claiming, and compounding. Therefore, if you want to save time and fees, you can continue to use the staking portal on Metis.

***

#### Omnichain Staking Contracts

<table><thead><tr><th width="326">Name</th><th>Address</th></tr></thead><tbody><tr><td>HeraStakingProxy</td><td>#</td></tr><tr><td>HeraStakingManager</td><td>#</td></tr><tr><td>HeraStakingController</td><td>#</td></tr><tr><td>HeraStakingCompounder</td><td>#</td></tr><tr><td>BaseAdminOperation</td><td>#</td></tr><tr><td>SimpleRewarder</td><td>#</td></tr><tr><td>RewardBooster</td><td>#</td></tr><tr><td>MpRewarder</td><td>#</td></tr><tr><td>HeraRouterManager</td><td>#</td></tr><tr><td>LZEndpointMock</td><td>#</td></tr><tr><td>MockOFTV2Token</td><td>#</td></tr></tbody></table>

**Note:** The deployment phase has not been completed yet.

{% hint style="danger" %}
_Please beware of fake tokens and refrain from interacting with any unofficial contracts!_
{% endhint %}
