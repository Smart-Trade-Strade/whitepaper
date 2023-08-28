# 🚧 Fail Guard

<figure><img src="../.gitbook/assets/smartlogo (2).png" alt=""><figcaption></figcaption></figure>

***

<details>

<summary>What is SmartGuard?</summary>

\-> When SmartGuard is activated, it initiates a pre-transaction simulation to assess the likelihood of encountering an execution error before broadcasting your transaction onto the network.&#x20;

\-> The primary aim of SmartGuard is to minimize unnecessary gas expenditure by avoiding the submission of transactions predicted to fail. However, this feature introduces a certain level of latency to your trading process, as the simulation must be completed prior to executing the actual trade.

\


</details>

<details>

<summary>Why did my transaction face failure despite SmartGuard being active?</summary>

\-> It's important to note that SmartGuard does not provide an absolute guarantee against all potential transaction errors. For instance, consider a swap transaction with a 5% slippage setting that is entirely valid and successfully simulates through SmartGuard. In scenarios where preceding transactions within the same block alter the price beyond the 5% range, your transaction may still encounter failure despite the activation of SmartGuard.&#x20;

\->This underlines the dynamic nature of the market and the inherent risks associated with trading.

\


</details>
