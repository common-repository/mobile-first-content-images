=== Mobile First Content Images ===
Contributors: erikportin
Tags: mobile first, content images, responsive design, mobile, image size
Requires at least: 3.0
Tested up to: 3.3
Stable tag: 0.1

Load smaller content images for mobile devcices with a mobile first approach

== Description ==

The plugin tries to detect what device the user is on. If it's detected as a mobile device or unknown the content images can be swapped with a smaller Post Thumbnail size of choice to save bandwidth.

= Requriements =

* PHP5
* Tested and works with Worpress version 3.0, 3.1, 3.2 and 3.3
* NOT working in Wordpress 2.9 and all version older than that
* Will probably cause some issues with other plugins trying to modify content images

= Test the plugin =

When testing if the plugin swapped your images use a real device or the iphone simulator. Changing the useragent to mobile on you desktop browser will not work. 

= Make it better =

You can find the code on [Github](http://github.com/erikportin/Mobile-Images/ "Github") and do whatever you like with it

= Thank you =

[phpQuery](http://code.google.com/p/phpquery/ "phpQuery") for making it easy to parse the html and [Categorizr](http://www.brettjankord.com/category/categorizr/ "Categorizr") for mobile first device detection.

== Installation ==

1. Upload `plugin-name.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

== Screenshots ==
1. Screenshot of admin section
