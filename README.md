# Chames
as in **ch**eap g**ames**, a small web application to watch the prices of your favourite games on [G2A](https://www.g2a.com)

![Screenshot](screenshot.png)

## Important note

Due to an API change by G2A this software is not functional at the moment. I'll try to fix it as soon as I find the time. Sorry. :-(

## Features
- sends you notification emails when a game is available for a specific price or cheaper with informations about the seller (after sending that email the alert for this game is disabled and can be enabled again from the overview page)
- an overview website for adding and deleting games
- API for the [Android app](https://github.com/lx4r/chames-app)

## Requirements
- PHP >= 5.4.0
- a webserver that supports `.htaccess` files
- a way to execute a script regularly (like cron or runwhen)

## Setup
1. go to `setup.php` with your browser and copy the configuration generated into `config.php`
2. change the other options in in `config.php` according to your needs
3. create a cronjob or something similar to execute `notifications_check.php` regularly (e.g. every day)
3. Enjoy!

## Powered by
g2a API, [REST Countries](https://restcountries.eu), [Bootstrap](http://getbootstrap.com)

----
This software is not in any way affiliated with g2a.com.  
Author: lx4r <https://l3r.de>

If you have a question regarding g2a-price-alert or if you want to give me feedback about my code please don't hesitate to contact me [via Twitter](https://twitter.com/lx4r) or [in some other way](https://l3r.de/en/contact).

The code of this project is 100% biodegradable and was written on happy keyboards.
