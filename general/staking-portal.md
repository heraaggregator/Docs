---
cover: ../.gitbook/assets/cover-gitbook-2024 (1).jpg
coverY: 0
---

# Staking Portal

{% hint style="danger" %}
## HERA Staking

The previous HERA staking system has been paused following the October 2026 token migration.

Eligible staked HERA balances and pending rewards were included in the official migration snapshot and migrated 1:1 together with holder balances.

No interaction with legacy staking contracts is required. Hera is currently evaluating the next generation of its token utility and protocol-revenue model. Details of any future staking or reward mechanism will be announced before activation.

**Status: Paused / Under Redesign**
{% endhint %}

Hera Finance has an A.I. assisted VaultManager that controls protocol revenue collected from all supported chains. Proceeds from swap transactions are used to develop and manage Hera's ecosystem. At the same time, a portion of all revenue can be transferred by the VaultManager based on recommendations from artificial intelligence to Hera Token ($HERA) holders through various methods.

Token buybacks are made possible with protocol revenue earned through exchange fees. Purchased tokens can then be burnt or added to the staking pool as a reward so that the holders can earn real yield.

Staking is a utility that allows Hera token holders to share in socialized protocol revenue.

Functionality Explained:

* **Claim:** Collects earned yield and sends it to your wallet
* **Compound:** Collects earned yield and adds it to your staked base principal.
* **Auto Compound:** Coming soon...
* **Staking Period:** The set time window rewards are obtainable. Date extensions are made regularly
* **HeraPower:** (Under Development): Participants will receive swap fee reductions based on their level of interaction and commitment to the ecosystem. This feature is exclusive to Metis Layer2.

***

### New Omnichain Staking Portal ✔&#x20;

{% hint style="warning" %}
**Status: Paused / Under Redesign**
{% endhint %}

{% embed url="https://portal.hera.finance" %}

***

#### **Legacy Omnichain Staking Architecture**

Introducing the omni-chain Hera Staking Portal!&#x20;

The $HERA staking model has now completely transformed and can be used independently across networks. With Hera Token's OFT upgrade, its dependency on specific chains has been reduced, creating a model that can expand to all networks. If Hera Token is deployed to a new chain, staking will be available shortly.

The new staking model is building on LayerZero, and the interchain messenger protocol is working seamlessly. Like OFT contracts, the staking protocol is distributed and managed from the Metis chain.

Function definitions and details:

* **Stake:** You can stake your Hera Tokens on one of the active chains.
* **Unstake:** You can withdraw your assets from the staking pool.
* **Claim:** Use the claim function to transfer your staking rewards to your wallet.
* **Compound:** It's a quick solution to claim and restake your staking rewards.
* Some more features coming soon ...

**Notice:**&#x20;

Metis is defined as the main chain for staking pools. So, if you stake Hera Tokens on other networks, the tokens will be moved to the Metis network after communicating with proxy and bridge contracts. During this process, gas/tx fees and transaction times may vary due to the involvement of bridge contracts. The same considerations apply to unstaking, claiming, and compounding. Therefore, if you want to save time and fees, you can continue to use the staking portal on Metis.

You will use the existing token for staking on Metis, while for new networks introduced with the OFT expansion, tokens with ownership of the OFT token contract will be valid.
