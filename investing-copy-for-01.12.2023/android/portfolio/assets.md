# Assets

Assets screen contains information about all assets by the selected account.

<figure><img src="../../../.gitbook/assets/image (939).png" alt=""><figcaption></figcaption></figure>

For each asset the following information is available:&#x20;

* Default symbol – allows showing the instrument name from the setting “Pricing instrument”.&#x20;
* Start day qty. (SOD qty) – asset quantity at the user’s account at the beginning of a day.&#x20;
* Current value for sell – allows showing the price of the asset, which is available for selling by Current price.&#x20;

Current value for sell = Available for sell \*Current price \* CrossPrice

When viewing an asset, the user can sell it or see the details of the selected asset. In order to do it, swipe left the card of the selected asset and the following buttons will become available:

<figure><img src="../../../.gitbook/assets/image (940).png" alt=""><figcaption></figcaption></figure>

To see the details of the asset, just tap the corresponding icon ![](https://lh6.googleusercontent.com/7v1BCnY_871B8leJv9GAWQEpdC1sKVAb8lnKl9dYWRVoUYsKYx87KLBGHKdRNqGIXFKsy6zwihTLVhigcUM_EM9hvdxyt6wEcH6wngp1kxDDMxYpiy-ed8_vuW6bm36LYeTIlWgr). The Asset details screen contains the following information:

<figure><img src="../../../.gitbook/assets/image (941).png" alt=""><figcaption></figcaption></figure>

* Asset name – name of the asset, which is set on a server.&#x20;
* Exchange – allows showing the exchange which is set on a server for the Default symbol.&#x20;
* Current value for sell – allows showing the price of the asset, which is available for selling by Current price.&#x20;
* Start day qty. (SOD qty) – asset quantity at the user’s account at the beginning of a day.&#x20;
* Intraday qty. – the quantity of the asset which was traded by all instruments for which this asset was pre-selected, but only for Product type=Delivery. The quantity of all Buy trades is counted with ‘+’, the quantity of all Sell trades is counted with ‘-‘.&#x20;
* Available qty. – quantity of the asset, which is available for selling.&#x20;

If Today traded qty.>=0, then Available for sell = Start day qty. Otherwise, Available for sell = Start day qty. - |Today traded qty.|&#x20;

* Current price – current Last price on the instrument Default symbol.&#x20;

The ![](https://lh4.googleusercontent.com/E9pMNEipoF7JLZCYXM7r7w6BzN7UTjNhXkt8A23tavf1o2Ig8uJ5v6iP62C173jnqLTjoRbpiqFmAnTAUIbg9NGSM2IDPwr___cwb5XmE-Y6uSADHyT29ZX48JAtFUVJ3fDrkDVf) button evokes Order entry with the Sell side of the order for the selected asset.

In the opened OE window a user has to go through the following steps to place an order:&#x20;

**Step 1:**&#x20;

* Select the order type - Market or Limit;&#x20;
* Set quantity.

**Step 2 (for Limit orders):**&#x20;

Set limit price.

<figure><img src="../../../.gitbook/assets/image (942).png" alt=""><figcaption></figcaption></figure>

**Step 3:**&#x20;

See the information about the order before sending.

<figure><img src="../../../.gitbook/assets/image (943).png" alt=""><figcaption></figcaption></figure>

After that a user can send the order:

<figure><img src="../../../.gitbook/assets/image (944).png" alt=""><figcaption></figcaption></figure>
