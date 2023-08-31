# ⏫ Buy Tokens

<figure><img src="../.gitbook/assets/covergitbook.png" alt=""><figcaption></figcaption></figure>

***

#### How to Adjust Slippage in the Telegram Bot:

<details>

<summary><strong>Private Tx Enabled (Automated Slippage):</strong></summary>

When the Private Transaction (Private Tx) feature is enabled, the slippage is automatically set to 10%. This setting is designed to safeguard transactions from potential sandwich attacks or frontrunning attempts.

</details>

**Customizing Slippage with Private Tx Disabled:**

If you wish to have greater control over your slippage settings, you can consider disabling the Private Tx setting. Here's how you can customize your slippage:

1. Disable the Private Transaction setting.
2. After disabling, the slippage configuration options will become visible, allowing you to tailor your preferred slippage settings.

#### **Configuring Slippage and Other Transaction Details:**

* **PAY:** Input the amount of BSC you intend to swap.
* **RECEIVE:** Provide the address of the token you're looking to acquire.

**Buy Settings (Expandable Panel):** Clicking on the Buy Settings panel will reveal additional options for configuring your buy transaction:

* **Use Private Transaction:** Decide whether you want to execute the transaction privately.
* **Frontrun Other Traders:** Opt to pay a higher gas fee for a chance to outpace other transactions and secure a priority spot.
* **Slippage:** Adjust the desired slippage by using the slider, or you can choose to enable Autoslippage.

**Simulation Panel:** The simulation panel displays key information about the transaction:

* **NAME:** Displays the name and symbol of the BSC20 token.
* **DEX:** Specifies the pool through which the trade will be routed.
* **AMOUNT:** Estimates the amount of the token you are expected to receive.
* **SLIP:** Indicates the minimum amount of the token you can anticipate obtaining.

<details>

<summary>Expanded Buy Settings:</summary>

* **Honeypot Detector:** Unibot employs an automatic check to determine if a token is a potential honeypot or scam token. A red bug icon indicates a token to avoid.&#x20;
* **Pending Notification:** A notification will appear in the top-right corner of your screen once the transaction is broadcast.
* **Success Notification:** A notification will also be displayed when the transaction is successfully included in the Binance Smart Chain network.

Remember that adjusting any of the Buy Settings will automatically trigger a re-simulation of the transaction. This comprehensive system allows you to fine-tune your trading experience within the Smart Trade Telegram Bot for optimal results.

</details>
