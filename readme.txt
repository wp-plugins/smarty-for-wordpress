=== Smarty for Wordpress ===
Contributors: phkcorp2005
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=9674139
Tags: smarty wp-smarty
Requires at least: 2.8.6
Tested up to: 2.9
Stable tag: 2.6.26

Smarty for Wordpress permits your Smarty template file to be embedded in a Wordpress post/page.

== Description ==

Do you have Smarty templates that you would like to use in your wordpress blog?

Do you want a fast track migration from Smarty to Wordpress?

Smarty for Wordpress is the first plugin which incorporates a complete distribution of the Smarty template engine as a Wordpress plug-in. You embed your Smarty template file by using a Wordpress short code with the Smarty template file name and any variable which you want to be passed to your Smarty template file.

There are many useful frameworks written in Smarty and NOT Wordpress, like XCart, that can NOW be implemented into Wordpress with minimal changes and ease?

Stop! Don't throw away that Smarty Template file, Download Smarty for Wordpress, install, activate and use that Smarty template file in Wordpress TODAY!!!

**Usage**

First you need to create your Smarty directories under the theme path that you will be
using, e.g.

themes/theme_name/templates<br>
themes/theme_name/templates_c<br>
themes/theme_name/cache<br>
themes/theme_name/config<br>

You may use Smarty for Wordpress either in you PHP/Theme files or from your Wordpress posts
and pages. To use the API, simple invoke the function that returns the page
information requested. There are three API's for this purpose:

If you wish to use Smarty in your custom worpress php files, then

1. Invoke the smarty_get_instance() function to get an instance of the Smarty class 
	with the directories preset to your current theme.
2. The simply use the Smarty class members as you would normally use, e.g $mySmarty->assign('name','value');
	to assign a template variable with a value.

You can also invoke the API's from your Wordpress pages/posts through short codes.

Create a Wordpress page and enter the following short code: 

	[smarty-display tpl=home.tpl] 
	
	where home.tpl is your smarty template located in the templates path

If you want to pass a single variable with the template, use 

	[smarty-display tpl=home.tpl name=myVariable value="some value"] 

	where name is the variable name specified in you smarty template file, and
	value is the value to be passed to your smarty template file that the above
	variable represents

== Installation ==

To instal this plugin, follow these steps:

1. Download the plugin
2. Extract the plugin to the `/wp-content/plugins/` directory
3. Activate the plugin through the 'Plugins' menu in WordPress
4. You are now ready to use the plugin. See the Admin page from Settings|Smarty for Wordpress for
tips and techniques on usage

== Credits ==

We make honorable mention to anyone who helps make Smarty for Wordpress a better plugin!

== Contact ==

Support for this plugin can be obtained from http://groups.google.com/group/smarty-template-engine
DO NOT ASK FOR SUPPORT FROM www.smarty.net!

PHK Corporation at phkcorp2005@gmail.com or www.phkcorp.com?do=contact

== Frequently Asked Questions ==

Please do not be afraid of asking questions?<br>

(There are no stupid or dumb questions!)


== Changelog ==

= 2.6.26 =
* Modified from Smarty version 2.6.26 to work as a Wordpress plugin

== Upgrade Notice ==

None