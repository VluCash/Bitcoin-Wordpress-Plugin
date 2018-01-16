Installation
-------------------

**1.1 Automatic installation**

Automatic installation is the easiest option as WordPress handles the file transfers itself and you don't need to leave your web browser. To do an automatic install of GoUrl Bitcoin Payment Gateway & Paid Downloads & Membership, log in to your WordPress dashboard, navigate to the Plugins menu and click Add New.

In the search field type "GoUrl" and click Search Plugins. Once you've found our plugin you can view details about it such as the rating and description. Most importantly, of course, you can install it by simply clicking Install Now.


**1.2 Manual Installation**

* Go to Wordpress Plugins > Add New
* Click Upload Plugin Zip File
* Upload the zipped gourl_wordpress file and click "Upload Now"
* Go to Installed Plugins
* Activate the "GoUrl Bitcoin Payment Gateway & Paid Downloads & Membership"



**2. Activate Bitcoin/Altcoin Payments in Plugin**

* Free Register or Login on the website https://gourl.io
* Create new payment boxes and get free Private/Public Keys https://gourl.io/editrecord/coin_boxes/0
* You will need to place Callback URL, please use: http://yoursite.com/?cryptobox.callback.php (the gourl wordpress plugin should be activated beforehand)
* Go to GoUrl Plugin Settings on your website and enter the private/public keys
* You can create Paid Products, Files, Membership, etc on your Wordpress Website

THAT'S IT! YOUR WEBSITE IS READY TO ACCEPT BITCOINS ONLINE!



**3. Move plugin data from one server to another server**

GoUrl wordpress plugin stores the data in four MySQL tables -

* crypto_files
* crypto_payments
* crypto_membership
* crypto_products

* Dump mysql tables either using mysqldump or if you are using PHPMyAdmin then Export the structure and data.
* Also copy gourl directory to new server - www.yourwebsite.com/wp-content/uploads/gourl/* 



**4. Testing environment**

You can use 500 free Speedcoins or Dogecoins for testing.
Url: [https://speedcoin.org/info/free_coins/Free_Speedcoins.html](https://speedcoin.org/info/free_coins/Free_Speedcoins.html)
The minimum account balance on GoUrl.io which our system will automatically transfer from your GoUrl internal wallet address to your external wallet address is 2 x mining fee. For Bitcoin this is 0.0005 BTC, and for Speedcoin and Dogecoin it is 5 coins, etc



More information at [https://gourl.io/bitcoin-wordpress-plugin.html](https://gourl.io/bitcoin-wordpress-plugin.html)       
 
 
