# WP Sharrre

**Contributors**:

* Derek Marcinyshyn [derek.marcinyshyn.com](http://derek.marcinyshyn.com)
* Julien Hany [hany.fr](http://hany.fr)

* **Version**: 1.3
* ~Current Version:1.3~
* **Requires at least**: 3.3
* **Tested up to**: 3.6
* **License**: GPLv2

Features
--------

* Google Plus
* Facebook
* Twitter
* Digg
* Delicious
* StumbleUpon
* Linkedin
* Pinterest default image and url
* Automatically grabs the first image on a page
* Google Analytics tracking
* Improve loading page
* Super lightweight

Description
-----------

WP Sharrre is a WordPress plugin based on a jQuery plugin that allows you to create sharing buttons for Facebook, Twitter, Google Plus and more.

More information on [Sharrre](http://sharrre.com/).

Must be using PHP 5.3.x + and WordPress 3.5 as it uses the new Media Uploader functionality.

Usage
-----

In your theme use

```php
<?php if ( is_callable( '\WP_Sharrre\View\Frontend::display_wp_sharrre' ) ) {
    echo \WP_Sharrre\View\Frontend::display_wp_sharrre();
} ?>
```

to display the Share buttons.

If downloading the zip file, be sure to unzip and rename the folder to ``` wp-sharrre ``` and remove the ``` -master ``` to make sure the plugin updater works.

Change log
----------

1.3

* Change order of Google Plus to be on the far right

1.2

* Added button class name to settings page to allow custom individual buttons
* Updated updater to version 1.6
* Updated sharrre.js to 1.3.4

1.1

* initial release