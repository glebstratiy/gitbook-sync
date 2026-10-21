# Settings

A user can access the "Settings" tab from the application’s "More" menu in order to manage "Defaults" and "Confirmations".

#### Defaults

In "Defaults" settings section you can adjust the following:

<figure><img src="../../.gitbook/assets/image (130).png" alt="" width="286"><figcaption></figcaption></figure>

* Order quantity – displays amount of lots for opening an order;
* Validity – allows specifying order validity by selecting among the following time frames: Day, GTC, IOC, GTD, FOK, GTS;
* Order type – allows to select one of the following orders: Market, Limit, Stop, Stop limit, Tr. Stop;
* Quantity in lots - if checked, quantity is displayed in lots, if unchecked – in units;
* Set SL/TP values in offset – if checked, the SL/TP prices are in offset, if unchecked they are in absolute values;
* Show offset in – allows to select one of the available modes for offset displaying: Ticks, Points;
* Use stop limit instead of stop – check to place stop limit orders instead of stop orders. When checked, it activates the "Limit offset, ticks" field;
* Buy TP trigger price - allows selecting price type for Buy Take profit order trigger;
* Sell TP trigger price - allows selecting price type for Sell Take profit order trigger;
* Buy SL trigger price - allows selecting price type for Buy Stop loss order trigger;
* Sell SL trigger price - allows selecting price type for Sell Stop loss order trigger;
* Select SL/TP trigger price in OE - if active, user will have a possibility to select SL/TP trigger price in Order entry panel.

#### Confirmations

‘Confirmations’ settings section allows to enable double-checking of the following actions by marking them as checked, after what the application will ask you to confirm these actions:

<figure><img src="../../.gitbook/assets/image (131).png" alt="" width="241"><figcaption></figcaption></figure>

* Order sending;
* Order modifying;
* Order executing;
* Order cancelling;
* Position modifying;
* Position closing;
* Alert removing.

#### Other

<figure><img src="../../.gitbook/assets/image (132).png" alt="" width="271"><figcaption></figcaption></figure>

The "Other" settings section cannot be displayed in the application settings if the biometric authentication is not checked in the system settings of the device or it is blocked.

Biometric authentication enables a user to log in to the mobile application more securely by using the Fingerprint or FaceID features.

<div align="center"><figure><img src="../../.gitbook/assets/image (133).png" alt=""><figcaption></figcaption></figure></div>

To apply Fingerprint in the application for subsequent logins, a user should put his finger on the sensor.

<figure><img src="../../.gitbook/assets/image (135).png" alt=""><figcaption><p><strong>Android</strong></p></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (136).png" alt=""><figcaption><p><strong>iOS</strong></p></figcaption></figure>

After this, the checkbox More -> Settings -> Other -> Biometric authentication becomes True.

A user should enter his password to confirm biometrics:

<figure><img src="https://lh7-us.googleusercontent.com/2d2GI4OmR68OHqkn8EbvaITOV7che_fRXZfk58jaBtMgRLYvASLNnJ-c0n9p6BSGoKPWlmvk3Xamloz3ZLlSC5c_lQW7vkOv8EELffOfNoh0AwIqBRazeL98oTi6kilGpRgC7WZr3SVccQkeoxlS_wI" alt=""><figcaption></figcaption></figure>

On subsequent calls of the Login screen form, if the Biometric authentication setting is checked in the application, then the following dialog box is automatically displayed:

<figure><img src="https://lh7-us.googleusercontent.com/EOhinwQmd5AEHj7gQhKXt7tkE4Ml9Nkj3dy7ZH_zgxM1XnYdrtctwsWvKu2sTfeAGa7WatwIApoxv0dDSSo46IAUEamoZr8kO9FkwrhWZC2255HnLlXaZ9GycW2HWYDss3esmVhzt_dV5YpfFgXniiY" alt=""><figcaption></figcaption></figure>

The user authentication occurs after putting a finger on the sensor and successful fingerprint recognition.

In case the FaceID feature is available and activated on the user device, it can be used as an additional application login option instead of the Fingerprint.

To deactivate Biometric authentication, uncheck the corresponding setting and then tap the "OK" button on the undermentioned screen:

<figure><img src="https://lh7-us.googleusercontent.com/4JIDB9GFig0Agy-QR6pDMhgjHNYnox7WFCERHuBVcM7GmCgQpU7zyNYvKY0ba6DoZoifDb--6RIkV92F3By6Ra-zoMM5Un6J7AQft90AzCsjqGTeifkTX-h9A7T_p-Z1sGCCflg6LCMb-LBHwTCWoIo" alt=""><figcaption></figcaption></figure>

#### Push notifications

TraderEvolution app provides the ability to receive push notifications on numerous events such as the daily loss limit warning, margin warning, receiving a new trading idea, etc. Upon receiving a push notification, the user can tap on it and thus open the application. Sending push notifications to the device is regulated by your broker, i.e. you cannot activate this function by yourself. If the user wants to disable receiving push notifications, he can do it in the settings of his device.

#### Alerts

This section allows to configure the alerts, the following settings are available:

<figure><img src="https://lh7-us.googleusercontent.com/y7ymqkSLP5lKS2rLAaN4Kn7xTOBcmNGNlbEN7vRslKK_8hF6kwF0Dpw5BXO57ivbBwD4bDfRYxQeOs293g_wVEc66ZsFoCk8hyb2i9ybEetIhbi9cHt6zPTbetkbnfrNUp1pTVCu7HQvbYYPHopH8bo" alt=""><figcaption></figcaption></figure>

* Notification – combobox for selecting the type of notification after alert triggering, multiselect is available:
*
  * Email – an alert containing the text from the ‘Alert message’ field will be sent to the user by email;
  * Push notification – an alert containing the text from the ‘Alert message’ field will be sent to the user via push notification;
  * Pop-up – an alert containing the text from the ‘Alert message’ field will be sent to the user in pop-up message;
  * Sound – a musical alert will be played to the user in the client.
* Alert type – allows to set an alert type. Available options are: Default by symbol, Ask, Bid, Last, Change%, Volume;
* Condition – allows to set an alert condition. Available values are: >,<,>=,<=;
* Importance – allows to define the alert importance, the following options are available: High, Medium, Low;
* After execute – allows to select alert behavior after execution. Available options are ‘Stop’ - alert is not active but stored in the list of alerts, and ‘Remove’ - alert is removed after execution.

{% hint style="info" %}
When there is no Internet connection, users with logging enabled are not allowed to change settings.
{% endhint %}
