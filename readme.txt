=== cleanSSL ===
Contributors: first10
Tags: ssl, https, insecure content
Requires at least: 3.0.1
Tested up to: 3.7.1
Stable tag: 0.1.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Get rid off SSL warnings about insecure content ( mainly images, stylesheets and javascript files) on pages served via https.

== Description ==
If you use https for the whole or part of your website then you might have come about the problem that when checking the SSL certificate for your site a warning appears that the current page contains insecure content. This insecure content is usually related to files ( ie images, stylesheets or javascript ) included on the page.

This plugin will make sure that if your site is being viewed via https that all references of http in the src attributes are removed. This means that all those files are now being served over https as well.

NOTE: At the moment images that are set within css or js files are not affected but we will be working on this. 

== Installation ==
1. Upload cleanSSL directory to the "/wp-content/plugins/" directory.
2. Activate the plugin through the "Plugins" menu in WordPress.
3. Done

== Screenshots ==
Will come shortly

== Changelog ==
= 0.1.3 =
* made plugin more reliable
= 0.1.2c =
* updated index.php version
= 0.1.2b =
* changed tested up to version
= 0.1.2a =
* forgotten to update readme.txt
= 0.1.2 =
* fixed issue with single quotes
= 0.1.1 =
* removed unwanted text
= 0.1 =
* Initial release.

== Upgrade Notice ==
= 0.1.2b =
* upgrade for latest bug fixes
= 0.1 =
* Initial release.