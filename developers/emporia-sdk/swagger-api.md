---
description: EmporiaSDK Swagger API - v1.1
cover: ../../.gitbook/assets/cover-gitbook2 (1).jpg
coverY: 0
---

# Swagger API

## Hera Dex Aggregator - Swap Protocol API

### Metis Mainnet Release

Using Hera Aggregation protocol API, you can find the best route to exchange assets and make the exchange.\
\
Progressing:

1. Lookup addresses of tokens you want to swap, for example ‘0xxx’ , ‘0xxxx’ for USDC -> METIS
2. Check for allowance and if necessary give approval for HeraAggregatorV2 contract to spend token (/allowance)
3. Monitor the best exchange route using (/quote)
4. When you ready use to perform swap (/swap)

{% hint style="info" %}
**EmporiaSDK is now available on Metis Mainnet.** Other chains are coming soon!
{% endhint %}

<details>

<summary><strong>Built with OpenAPI &#x26; Swagger!</strong></summary>

Design, describe, and document your API on the first open source editor supporting multiple API specifications and serialization formats. The Swagger Editor offers an easy way to get started with the OpenAPI Specification (formerly known as Swagger) as well as the AsyncAPI specification, with support for Swagger 2.0, OpenAPI 3.0, and AsyncAPI 2.\* versions.

</details>

### Swagger Paths:

#### Allowance&#x20;

{% swagger src="../../.gitbook/assets/EmporiaSDK-Metis-v1-1.json" path="/allowance" method="get" expanded="true" %}
[EmporiaSDK-Metis-v1-1.json](../../.gitbook/assets/EmporiaSDK-Metis-v1-1.json)
{% endswagger %}

{% code overflow="wrap" %}
```
// Example Query:

GET https://pathfindersdk.hera.finance/allowance?account=0x0000000000000000000000000000000000000000&amount=1000000&tokenInAddress=0xEA32A96608495e54156Ae48931A7c20f0dcc1a21
```
{% endcode %}

#### Quote (Pathfinder)

{% swagger src="../../.gitbook/assets/EmporiaSDK-Metis-v1-1.json" path="/quote" method="get" expanded="true" %}
[EmporiaSDK-Metis-v1-1.json](../../.gitbook/assets/EmporiaSDK-Metis-v1-1.json)
{% endswagger %}

{% code overflow="wrap" %}
```
// Example Query:

GET https://pathfindersdk.hera.finance/quote?account=0x0000000000000000000000000000000000000000&tokenInAddress=0xDeadDeAddeAddEAddeadDEaDDEAdDeaDDeAD0000&tokenInChainId=1088&tokenOutAddress=0xEA32A96608495e54156Ae48931A7c20f0dcc1a21&tokenOutChainId=1088&amount=100000000000000000000&type=exactIn
```
{% endcode %}

#### Swap

{% swagger src="../../.gitbook/assets/EmporiaSDK-Metis-v1-1.json" path="/swap" method="get" expanded="true" %}
[EmporiaSDK-Metis-v1-1.json](../../.gitbook/assets/EmporiaSDK-Metis-v1-1.json)
{% endswagger %}

{% code overflow="wrap" %}
```
// Example Query:

GET https://pathfindersdk.hera.finance/swap?account=0x0000000000000000000000000000000000000000&tokenInAddress=0xDeadDeAddeAddEAddeadDEaDDEAdDeaDDeAD0000&tokenInChainId=1088&tokenOutAddress=0xEA32A96608495e54156Ae48931A7c20f0dcc1a21&tokenOutChainId=1088&amount=100000000000000000000
```
{% endcode %}
