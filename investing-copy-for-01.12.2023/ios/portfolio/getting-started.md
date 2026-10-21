# Getting started

The Portfolio functionality allows an Investor to monitor and control profit and risks in his portfolio to get subsequent income. The Portfolio screen is shown immediately after opening the Investing application.

<figure><img src="../../../.gitbook/assets/image (1058).png" alt=""><figcaption></figcaption></figure>

At the top of the screen a user can see the informational card that displays info about the account selected in the Account lookup.

<figure><img src="../../../.gitbook/assets/image (1059).png" alt=""><figcaption></figcaption></figure>

* **Pending cash** shows Projected balance(Balance+ unrealized P/L).&#x20;
* **Today return** value is located next to Pending cash. It shows the percentage of growth/drawdown of Pending cash compared to the last trading day. Calculations:

<figure><img src="../../../.gitbook/assets/image (1061).png" alt=""><figcaption></figcaption></figure>

where:&#x20;

_**CurrentProjectedBalance**_ - current value of Projected balance by the account;&#x20;

_**Deposit**_ - the sum of all Deposit transactions by the account performed after the time when the last value of the Projected balance was saved.&#x20;

_**Balance credit**_ - the sum of all Balance credit transactions by the account performed after the time when the last value of the Projected balance was saved.&#x20;

_**|Withdrawals|**_ - modulus of the sum of all Withdrawal transactions by the account performed after the time when the last value of the Projected balance was saved.&#x20;

_**|Balance debit|**_ - modulus of the sum of all Balance debit transactions by the account performed after the time when the last value of the Projected balance was saved.&#x20;

_**Transfers**_ - the sum of all Transfer transactions by the account performed after the time when the last value of the Projected balance was saved.&#x20;

_**Adjustment**_ - the sum of all Adjustment transactions by the account performed after the time when the last value of the Projected balance was saved.&#x20;

_**|TransferAndWithdrawal fees|**_ - the sum of all Transfer fee and Withdrawal fee transactions by the account performed after the time when the last value of the Projected balance was saved.&#x20;

_**LastProjectedBalance**_ - the last value of the Projected balance saved to the database for the account by the Investing maintenance scheduler task. If the LastProjectedBalance value = 0, then use the following formula to calculate the Today return value:

<figure><img src="../../../.gitbook/assets/image (1062).png" alt=""><figcaption></figcaption></figure>

where:&#x20;

II - investment income for the current day can be calculated by the following formula:&#x20;

II = CurrentProjectedBalance + (|Withdrawals|+|Balance debit| - Transfers -Adjustment + |TransferAndWithdrawal fees| - Deposit-Balance credit)

* **Open P/L** - Net profit or loss for all open positions and assets.&#x20;
* **Available cash (Available funds)** - the amount of funds to place new orders.&#x20;
* <img src="https://lh6.googleusercontent.com/awQyHO8SWAC2h9LzF2Vpsx2qTiRprniWVVWIgL5Z88p3-bNd8XX_yN_DlapCsgd3btNJ05HbtY1v4-FUMbElh0l62IouWeO8TDkxTq-7vz8GNdAUA6hWvaRsopCkkZXz3dnN_3UW" alt="" data-size="line">**button** allows hiding the following values: Pending cash, Open PnL, Available funds.
* <img src="https://lh5.googleusercontent.com/-Nkq17fHV2lwCMhV43poK58vZWzHhhrS0pHBwRhA2_nyJrbH0rVSKqwEimEhBWN0iUZw4by95l9LRBdZXYUFx8DllhT9bbJW7ZuI9VJMalwGpO98f8fs_DqDrCWRW9yYcifbAVHj" alt="" data-size="line">**button** allows opening a chart that shows the growth/drawdown of Pending cash. Tap the ![](https://lh3.googleusercontent.com/gRq0WOBOumOD8K1aXqR2LrBQdEK7ytcj2zB0ELZdPAiFSZyDwAoFibxh1dwQP6d6fr9EBkOhSFBvBhEkmNiTuvV8HboPj-iaWQhyCax0mD1Mlb5ZfR44Sp6BuS9PMbTwZrqLQNQ1) **button** to close the chart.

<figure><img src="../../../.gitbook/assets/image (1063).png" alt=""><figcaption></figcaption></figure>

The horizontal axis shows the date, the vertical axis shows the percentage change of the Cumulative daily return value.

**Pie chart**\
The pie chart displays the percentage ratio of all open positions by instrument types.

<figure><img src="../../../.gitbook/assets/image (1064).png" alt=""><figcaption></figcaption></figure>

The number of chart sectors corresponds to the number of instrument types included in the portfolio, as well as Cash. The percentage of each instrument type in the portfolio is calculated by the following formula:

<figure><img src="../../../.gitbook/assets/image (1065).png" alt=""><figcaption></figcaption></figure>

where:

-i - instruments of the same type in the investor's portfolio, i = 1...n, n - number of instruments of the same type in the portfolio&#x20;

-∑Position value(i) - total value of all positions of the same instrument type in the portfolio.&#x20;

-Projected balance - future, estimated balance of the account with accrued and unaccrued profits/losses. Percentage of Cash in the portfolio:

<figure><img src="../../../.gitbook/assets/image (1066).png" alt=""><figcaption></figcaption></figure>

In the center of the diagram a user can see the value of the largest share of the instrument type in the portfolio in percentage, and the instrument type. Next to the pie chart a user can see the list of instrument types included in the portfolio. The colors of the instrument types correspond to the colors of chart sectors.

Under the diagram a user can find the following tabs: Positions, Assets, Orders, Operations.

<figure><img src="../../../.gitbook/assets/image (1067).png" alt=""><figcaption></figcaption></figure>
