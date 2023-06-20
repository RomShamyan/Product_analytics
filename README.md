# Product_analytics
### Analysis of user behavior of a home delivery company and evaluation of the effectiveness of their acquisition channels. Uploaded data from AppMetrica for the period from January 1 to March 31, 2020, only for users registered after January 1, 2020.
Data Description:
- date – date of the event;
- event - event:
  • app_install - Installing an application
  • app_start - open applications
  • register - register
  • search - go to the product search page (catalogue)
  • open_item - open item
  • choose_item - send item to cart
  • tap_basket - go to the basket
  • purchase - purchase confirmation
- gender - gender of the user;
- os_name - user platform;
- city – user's city;
- device_id - user device ID;
- urm_source - the channel from which the user came:
- yandex-direct - Yandex direct
  • google_ads - advertising on Google
  • vk_ads - advertising in VK
  • instagram_ads – ads on instagram
  • facebook_ads - facebook ads
  • referal - promotion "bring a friend"
  • If there is ‘-’, then the channel is not defined or it is a direct download of the application or the visit is not from advertising
- purchase_sum - the cost of the purchase (when the 'purchase' event occurs).

In the upload, only unique user actions for each day
You can bypass the installation stage of the application if it was installed earlier
It is possible to bypass the registration stage if the user was already logged in at the time of the session. 
However, unregistered users cannot make a purchase.
