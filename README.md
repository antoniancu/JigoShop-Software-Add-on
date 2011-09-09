JigoShop Software Add-On

This plugin extends the WordPress [JigoShop](http://jigoshop.com/) e-commerce plugin by offering the disabling and enabling certain functionality which transform the shop into a software selling hub, include a full API for license generation, license activation, license retrieval, activation e-mails, stats and more. 

The code is well documented (inline) with more documentation to come. The project started off as a private client request, but is now public for anyone to collaborate on. That being said, the client continues to use this plugin and its updates, and thus there may be certain constraints before pushing an update (otherwise a branch may be required). We are open to any suggestions :)

Changelog
===========

### 1.8
* Add timestamp to all API requests
* Fix PHP notice bug with the updater class from 1.7

### 1.7
* Ability to resend purchase e-mail to customers from backend
* Fix PHP memory bug with the updater class

### 1.6
* Store transaction ID for each order
* Process and send e-mail with Paypal IPN response, making it more bullet-proof

### 1.5.3
* fix a WP_Error bug with the updater class

### 1.5.2
* PHP < 5.3 backwards compatibly for removing the pragma header

### 1.5.1
* Remove pragma header

### 1.5
* Set proper headers for IE7 in the API

### 1.4
* disable email now button after click, fixes issue #15

### 1.3
* One-click plugin updates in the backend (a la typical WordPress), still only hosted on GitHub

### 1.2
* Initial Public Release
* Proper decimal formatting for prices on purchase pages (front-end)
* Allow searching for orders via the activation e-mail in the admin
* Removed direct references to client site/project in favour of more generic examples and strings

### 1.1
* Added an import page in the admin which allows to import orders 
* See [this page](https://github.com/jkudish/JigoShop-Software-Add-on/wiki/Import-Instructions) for details on the import routine

### 1.0
* Initial Private Release

Current Version
===============

The line below is used for the updater API, please leave it untouched unless bumping the version up :)

~Current Version:1.8~