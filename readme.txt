== TJ Breadcrumb ==
Contributors: Tanvir, Theme Junkie.
Tags: Breadcrumb, Navigation, Trail.
Requires at least: 3.6
Tested up to: 4.2.2
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

==Description==

This plugin will add the functionality to display a full chain of links to the current page.
 #Breadcrumbs is appearing on a following types of WordPress pages:

   # paged navigation (like sitename.com/page/2/);
   # category archive;
   # tag archive;
   # daily archive;
   # monthly archive;
   # yearly archive;
   # author archive;
   # custom post type;
   # single post page;
   # single page;
   # attachment page;
   # search results;
   # 404 error page.

==For the Develoer ==
   #adding a page number (if archive page is second or more);
   #custom symbol of delimiter;
   #custom text for a ‘Home’ link;
   #current crumb styling;
   #integrated Google structured data.
 

==Installation==

This section describes how to install the plugin and get it working.

e.g.

1. Upload `TJ Breadcrumb` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Then paste the following php code in a place of your theme, where breadcrumbs must appearing:
	#code: 
	<?php
	if (class_exists('breadcrumb')) $obj = new breadcrumb; $obj-> tj_breadcrumb();
	?>

4. You have done.
= Support =

* Get [support](tanvir.focus@gmail.com)

= Plugin Info =
* Developed by [Tanvir](https://twitter.com/TanvirFocus) & [Theme Junkie](http://www.theme-junkie.com/)
* Check out the [Github](https://github.com/themejunkie/TJ-Breadcrumb) repo to contribute.

==Changelog==

Version: 1.0
* Initial Release
