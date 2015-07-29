=== 2MB Autocode ===
Contributors: lilmike, stormdragon2976
Donate link: http://2mb.solutions/donate
Tags: autocode, code placement, automatic, php, html, preformatted text, top, bottom, modify posts
Requires at least: 2.7.0
Tested up to: 4.0
Stable tag: 1.1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin allows you to place predetermined text/html/php at the top or bottom of posts.

== Description ==

This plugin, developed by [2MB Solutions](http://2mb.solutions/), allows you to place predetermined text/html/php at the top and/or bottom of each post. In addition, you can override the placing of text at the bottom and/or top of a specific post, override the placing of text on the homepage or on a post individually, or run arbitrary php inside a post.

For more on 2MB, please visit (http://2mb.solutions/).

== Installation ==

Installation is extremely simple!

1. Visit your wordpress dashboard and click add new under plugins.
1. Either search for 2MB Autocode and find it in the repository then click install and confirm that you want to, or upload a downloaded zip file then click install.
1. It should install.

That's it! Now you can enjoy your 2MB goodness!

Feel free to mess around with the settings under settings > Autocode.


== Frequently Asked Questions ==

= How do I remove the text from a specific post! HELP! =

Simply put ##no_top## or ##no_bottom## anywhere in the post, and it will remove those tags, and not put the text on bottom or top depending on which tag(s) you entered. In addition, if you put ##no_top_home##, ##no_bottom_home##, ##no_top_post##, or ##no_bottom_post##, it will remove the text from either the top or bottom of either the post page or the homepage, no matter what is set in the settings.

= How do I suggest a feature or new plugin? =

We're glad you asked! We're always looking for new ways to improve, whether in the realm of new plugins, or upgrading existing ones. Please go to our [website](http://2mb.solutions/), and click contact us. There you will be able to email us a message. Rest assured we read every email we receive and strive to respond to as many as possible!

= How do I run php inside a post? =

Simply enclose the php you want to run inside [php and ]/php] tags.

For example, to echo hello world in the middle of a post, do the following:

[php] echo("hello world!");[/php]

= How do I make the text go on the homepage without setting the checkbox! =

Simply put  ##do_top_home## or ##do_bottom_home## anywhere in the post.

== Screenshots ==

No screen shots at the moment. Sorry!

== Changelog ==

= 1.1.1 =
*Added documentation to the plugin itself.
*Added ##do_top_home## and ##do_bottom_home## to put text on the top or bottom of a post on the homepage even if the checkbox in settings is unchecked.

= 1.1 =
*Added ##do_top## and  ##do_bottom## to place the bottom or top text anywhere in a post.
*Added ##no_top_home##, ##no_bottom_home##, ##no_top_post##, and ##no_bottom_post## to override the placing of text specifically on the home or post pages.
*Added [php] PHP CODE HERE [/php] to run php inside a post.
*Very important! Fixed an issue where php at the top or bottom of posts would not run, and could possibly crash programs or make them not work correctly.
*Fixed a possible bug where php code in the top or bottom of the post may have been echoing to the wrong part of the screen.

= 1.0 =
*First release. woohoo!

== Upgrade Notice ==

= 1.1 =
If you were using php at the top or bottom of a post, please upgrade to this version as this fixes a possibility that the php code would not run or the php may have echoed to the wrong part of the screen. In addition if you want to run php code in your posts without having to add it to every post, then you may like this release. Also, if you wish to turn off the placing of text on a per post basis for the home and/or single post pages, this update is for you.

= 1.0 =
Because this plugin is awesome! Seriously, go try it! ;-)
