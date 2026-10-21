# Option chain

The Option chain screen shows detailed information about a specific option contract and allows a user to trade from this panel.&#x20;

<figure><img src="../../../.gitbook/assets/image (750).png" alt=""><figcaption></figcaption></figure>

Swipe left the instrument at the Watchlist screen and select the corresponding item to open the Option chain panel.

<figure><img src="../../../.gitbook/assets/image (751).png" alt=""><figcaption></figcaption></figure>

Tap the Symbol info to open information by the instrument in a new window. Tap the “Back” button in Symbol info to get to the chart.&#x20;

Under the header of the Option chain screen a user can see the Info bar which displays the following data:

* Last - last price by underlier;
* Change, % - change in percentage by underlier;
* Volume - volume by underlier;
* Previous close - the previous day's close price.

The Option chain table contains 3 columns:

* Calls - this column shows the cards of Call strikes that display the following information: Ask, Bid, IV, OI (Open interest), Change. Other parameters can be configured in the Panel settings;
* Strike - the Strike price;
* Puts - this column shows the cards of Put strikes that display the following information: Ask, Bid, IV, OI, (Open interest), Change. Other parameters can be configured in the Panel settings.

In Option chain panel the coloring method “By difference” is used. Depending on what type of price change comes at a certain strike to buy or sell, it is highlighted in green or red.

IV (Implied volatility) column shows the expected volatility of the option which characterizes the degree of underlier price volatility. If IV is high, strong fluctuations of underlier price are expected.

The Open interest column shows the total amount of open positions.

Tap Ask or Bid button to select the strike (Leg). It is possible to select several strikes. Tap one more time to delete the Leg from selected ones. Orders can be added to the strategy from different option series for a given underlier.

The undermentioned screenshot shows the filter by the number of displayed strikes:

<figure><img src="../../../.gitbook/assets/image (752).png" alt=""><figcaption></figcaption></figure>

### Analyzer

By tapping ![](https://lh6.googleusercontent.com/BsMx81Eg5KgMpqby1GVEg7QGpty8dIWA9ma-m59Zybo9WVTros8rDvyCrKyNRMk0NFPjv7ExhhosjmLjN71bZbTW6fM2Nz6DuA_qkaEJJR8r4j776gqv_Gvq4guU9fd0l0AihefGuBgh2wz1GNaUn8k) button, a user will get to the graphical data section:

<figure><img src="../../../.gitbook/assets/image (753).png" alt=""><figcaption></figcaption></figure>

“Legs” section displays the list of orders. Tap ![](https://lh4.googleusercontent.com/z8LZSgqjD-tbLtIPanwT21XKJw9-EZYOEZsdCEPvzyTfEnZhQyRynB0UzR9N_SL-alYKy6UUeuQXUACr74aZEsO5WDeLUnO5I34TfcOwBSs4ZM6wjZ9JdhGtNKCcSl-aXWHOa8HrXbrXxQp_-PZ5N1M) button to show/hide this section. Tap the “Add underlier” button to add a Leg by underlier. The following parameters are available for viewing:

* Intrinsic P/L - profit calculated by the Expiration curve;
* P/L - profit calculated by the Current curve;
* What if - profit calculated by the Timeline curve;
* Potential gain - the largest positive P/L value for the total profile;
* Potential loss - minimum negative P/L value for the total profile.

Greeks are the coefficients used for the characteristics of option cost sensitivity to the changing of various values: Delta, Gamma, Vega and Theta.

* Delta – is the first derivative of the option price by the underlier price; shows how option price will be changed in points, if the underlier price changes by 1 point.
* Gamma – is the second derivative of the option price by the underlier price; shows the rapidity of the option delta change.
* Vega – is the first derivative of the option price by volatility; shows how option price will be changed in points, if the volatility changes by 1%.
* Theta – is the first derivative of the option price by time; shows how the option price will be reduced after one day.

To send orders from the Option chain panel, open Order entry by tapping the<img src="../../../.gitbook/assets/image (755).png" alt="" data-size="line">button:

<figure><img src="../../../.gitbook/assets/image (754).png" alt=""><figcaption></figcaption></figure>

Order entry screen is divided into groups for each Leg. If a trader has several accounts, it is possible to change them, using a control displayed above the list of Legs. Tap ![](https://lh5.googleusercontent.com/O5xFJDV63t2mpeA5b8pOZpb4uXBrcgnquBEum91MeYkFzmPgrNW5-Kul3mbwORJUTsm84HxRPGOla8Zl7YSUecmFuC1XZCDInyV9qIPHp1zWcSjSeS2OX4sOIvCvcQ4bMHZ08_V0D3OOvgZ_aNQ-VaE) button to delete the Leg from the list. Tap ![](https://lh5.googleusercontent.com/A7ajPtiTEmbY7-9JoOmmyBRP_S5ekdJgSzB6Cl7vdWUF4VoSpPA5fVcsq8t5prpvLGal1CxkKoKIR0dJvGlW2yEWaj8FobeGNoi14EuL1tMos611qSqSx2qIIDQ2zWPiE9RMhaBUjS3IecIF7cFdJC8) button to show/hide the details of a Leg. Tap the “Place strategy” button to send orders.

### **Settings**

In order to manage the panel settings, tap the ![](https://lh6.googleusercontent.com/FfyMDu4DsRh_HVfNrJInc_UOYq_Ux3ueqTeiQ2f_YbLqO_CbBSQibssvM0sdNmaC0oAoVOOmg9-HCe2Z9AA7MkJBwo2MO6sVAvRwiV4wsv6NgiP7KGwsKwhr079YmvJutglCa1MG) button and the following screen will be opened:

<figure><img src="../../../.gitbook/assets/image (756).png" alt=""><figcaption></figcaption></figure>

A user can configure settings in the “Column editor”, “Calculations” and “Analyzer” sections.

* Column editor - in this section a user can activate/deactivate the necessary parameters for displaying in the Call and Put options card;
* Calculations - this section contains parameters that will affect the calculations;
* Analyzer - this section contains a setting that allows a user to choose the chart type and the settings that are used to calculate the option profile.
