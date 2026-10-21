# Account details

The Account details screen is accessible through the Watchlist, Positions and Orders screens. Tap the ‘Projected balance’ section to open Account details screen. To select the account available for a user, tap the<img src="../../../.gitbook/assets/image (739).png" alt="" data-size="line">button at the top of the screen:

<figure><img src="../../../.gitbook/assets/image (740).png" alt=""><figcaption></figcaption></figure>

In order to view detailed information about an account, tap its name.

<figure><img src="../../../.gitbook/assets/image (741).png" alt=""><figcaption></figcaption></figure>

P/L, % = Open Gross P/L \* 100 / (projectedBalance - Open Gross P/L)&#x20;

Risk level – displays how an account is close to portfolio liquidation.

<figure><img src="../../../.gitbook/assets/image (742).png" alt=""><figcaption></figcaption></figure>

* Balance – current realized balance of the account. If there is trading with pending valuation, balance won’t change before clearing, on which P/L will be credited by covered trades or delivery of funds will be performed by uncovered trades; Fees are charged off from the balance at the time of accrual;
* Projected balance – future balance which includes all accrued and not accrued profit/loss. After closing all positions, accrual of fees and assets' delivery, the balance becomes equal to a projected balance:

Projected balance = Balance + Unsettled cash + Loss + Profit + Blocked for Stocks + Option premium, where:

Unsettled cash – cash sum of unsettled account operations, which have not been delivered to an account yet and will be delivered in accordance with T+n settlement system;

Profit/Loss – current open profit/loss by positions;

Blocked for Stocks – amount of funds debited from a balance in case of Equities trading. After closing such position, funds will be returned to an account:

Blocked for stocks = abs (∑ Stock operation), abs - module.

Option premium – option premium value.

Option premium = ∑ (Open price \* Qty \* Lot size \* Cross price), where:

Open price – an average price of a position opening;

Qty – a position's qty in lots;

Lot size = Tick cost / Tick size;

Cross price – an average cross price of a position opening for converting into account's currency.

* Available funds – amount of funds which can be used for placing a new order.&#x20;

Available funds = Balance& All risks - Margin used;

* Margin available – full margin which is available to maintain portfolio on the current moment.&#x20;
* Init. margin req – amount of the initial margin blocked for all positions and orders taking into account the margin crossing;
* Warning margin lvl – shows Maintenance margin level when the margin warning message is sent:

Warning margin lvl = (Margin warning% / 100) \* (Balance\&All risks - Stock orders req);

* Waived margin –the amount in the account currency that is deducted from Initial and Maintenance margin requirements for the account;
* Blocked balance – balance blocked by broker or by user for withdrawal/transfer;
* Cash balance – current cash balance of the account;
* Unsettled cash – сash sum of unsettled account operations, which have not been delivered to an account yet and will be delivered in accordance with T+n settlement system;
* Incoming funds – the total amount of all unsettled Deposit account operations in the account currency;
* Withdrawal available – shows an amount of funds that you can withdraw immediately from your account:

Withdrawal available=Available  funds – Credit value – Profit – Unsettled profit — Unsettled loss available for withdrawal+ Unused unsettled negative cash for stocks – Unsettled positive cash for stocks + Unused unsettled negative premium — Unsettled positive premium + Unsettled premium from open sell — Used premium from open sell -Stocks liquidity + Withdrawable cash for stocks + Withdrawable unsettled profit/loss + Withdrawable unsettled collateral + Unused intraday initial margin — Used overnight initial margin for intraday — Accrued dividends + Withdrawable options premium - ∑Unsettled account operation(Deposit)

{% hint style="warning" %}
"Unused intraday initial margin" and "Used overnight initial margin for intraday" participate in the calculation only during those periods of the trading session for which Is Intraday = true. For other periods, they do not participate, since the margin is already blocked by Overnight coefficients.
{% endhint %}

* Init. margin req, % – shows how much margin is used in relation to Balance\&All risks:

Initial margin req, % = (Initial margin req/ (Balance\&All risks - Stock orders req))\*100%;

* Blocked for stocks – amount of funds debited from balance in case of Equities trading. After closing such position, funds will be returned to account;
* Stocks value – total cost of stocks, positions which were opened on the selected account:

&#x20;Stocks value = ∑ (Current stock price \* Amount \* Cross price), where:\
&#x20;Amount – a current stocks' quantity in the position 'Qty \* Lot size'; Qty is qty in lots.

* Open positions – currently opened positions;
* Working orders – all created orders which are visible for a user;
* Option premium req – option premium for buy orders;
* Stocks liquidity – a part of a total cost of assets, which is accounted in available margin if there are assets on the account of a trader.

Stocks liquidity = ∑ (Amount \* Price \* CrossPrice \* (Liquidity rate/100)) Amount - a current stocks' quantity on the account 'Qty \* Lot size'; Qty is qty in lots.

* Stocks orders req – total margin blocked for Equities;
* Option value – сurrent option value in portfolio. Can be positive for a long Net position, or negative for a short Net position.&#x20;

Option value = ∑ (Current option price \* Amount \* Cross price), where:

Current option price – a current price of an option;\
Amount – a current amount of options in a position;\
Cross price – a current cross price in account's currency.

* Today’s net profit – Net Profit/Loss for today;
* Today’s fee ­– amount of fees paid for today;
* Warn. margin req. – warning margin requirement for positions and orders;
* Warn. margin req.% – warning margin requirement in relation to Balance\&All risks;
* Margin before warning – margin available before the warning triggering;
* Day trader pattern protection –  displays whether protection against accidental marking the account as the Day trader pattern is activated. Available states are ‘Enabled’ or ‘Disabled’;
* Available day trades –  displays the number of intraday trades that can be performed before the system classifies this user/account as a Day trader pattern;
*   Open gross P/L(i) – current unrealized Gross P/L for each position at the account:

    &#x20;Open gross P/L = Sum (Open gross P/L(i));
*   Open net P/L(i) – current unrealized Net P/L for each position at the account:

    &#x20;Open net P/L = Sum (Open net P/L(i));
* Stop out value – value that should be reached in order for Stop out to be triggered:                                                 Stop out value = Maint.margin req/ (Stop out level/100).

**Account actions**&#x20;

Account actions - is a set of actions that are allowed to the particular account.

It is available in the Account menu ![](https://lh7-us.googleusercontent.com/camE1ROtFZ-Vo2s_yyW-rRrjdoYmLZCUdY_oPNKewV9C2RHQq6vM76iDk2sbc3Y2j2MyGVgSHebsdi5GfrHoW1ekkz6hmHEAUn9Dx-RzNGV3i11Gf3Un6uD-vOmn5Zfe3cDsLY7J1oQ1BFouCkJG9xA) when it is allowed  for this account:&#x20;

<figure><img src="../../../.gitbook/assets/image (743).png" alt=""><figcaption></figcaption></figure>

* Withdrawal - a process of taking money out of an investment account.
* Change password - an option for replacing current password with a new one.
* Close account request - an option for users to send requests to close their accounts.

**Close account**

After clicking the ‘Close account’ option, the following confirmation screen will appear:&#x20;

<figure><img src="../../../.gitbook/assets/image (744).png" alt=""><figcaption></figcaption></figure>

By clicking the “Send request” button the request for closing an account is created and the following screen with ability to cancel a request will appear:

<figure><img src="../../../.gitbook/assets/image (745).png" alt=""><figcaption></figcaption></figure>

Important note - while the request is being processed, there are no restrictions on the use of the account.

The following deal ticket will also be shown, by clicking on which the status of the request will be shown:

<figure><img src="https://lh7-us.googleusercontent.com/tFuZbnQWutFdEX1NpjdVkImRewpaZapPv7MmB2FIRVmn06ZjYTPHV8cXryOjwuII_kiEtX74jr8yTDmN1-DxX2E_iyeC3yZuMLBGNj_G69uTD3vAaj_hge1FR7R6C-k1J-a4bo4AYjGgiEJqk_JyYZs" alt=""><figcaption></figcaption></figure>

There are 4 possible statuses of the closing account requests:

* Submitted - request has been successfully submitted;
* Accepted - the necessary actions will be completed shortly and the account will be closed;
* Rejected - request is rejected;
* Cancelled - request is cancelled.

By clicking on such a notification, the following screen with additional information will appear:&#x20;

<figure><img src="../../../.gitbook/assets/image (746).png" alt=""><figcaption></figcaption></figure>
