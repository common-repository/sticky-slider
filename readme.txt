=== Responsive Sticky Slider ===
Contributors: themeisle 
Tags: slider, slides, sticky, featured, cycle, jquery, responsive
Requires at least: 4.3
Tested up to: 4.6
Stable tag: 1.2.5
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html

== Description ==

Simple, responsive post slider with pagination (previous/next and page numbers).

Select transition type, easing type, number of slides, timeout and custom category and place the shortcode or the template tag in your post or page.

The plugin is responsive and adapts to any page width, either for desktop or mobile systems.

Check the [official homepage](https://getbutterfly.com/wordpress-plugins-free/#sticky-slider "getButterfly") for feedback and support.

== Installation ==

1. Upload to your plugins folder, usually `wp-content/plugins/`
2. Activate the plugin on the plugin screen.
3. Add `<?php if(function_exists('sticky_slider')) sticky_slider();?>` to your index template.
4. Configure the slider in Settings | Sticky Slider

== Frequently Asked Questions ==

= How do I add the slider to my blog? =

You need to add the `<?php if(function_exists('sticky_slider')) { sticky_slider(); } ?>` PHP function to your template or place the `[sticky-slider]` shortcode anywhere on your post or page using the editor.

== Screenshots ==

1. Front-end slider with navigation and pagination
2. Back-end section

== Changelog ==

= 1.2.5 =
* UPDATE: Added getButterfly ad box

= 1.2.4 =
* UPDATE: Updated WordPress version
* UPDATE: Added help and support links

= 1.2.3 =
* Added license link
* Added donate link

= 1.2.2.1 =
* Fixed a PHP warning

= 1.2.2 =
* Better script inclusion
* No inline CSS styles
* Speed improvements

= 1.2.1 =
* Added transition options
* Added easing options
* Added custom category option
* Added localization options
* Updated Cycle plugin
* Updated query type
* Updated plugin compatibility

= 1.1.2.2 =
* Changed author URL address, again
* Fixed sticky posts behaviour
* Removed categories from options panel

= 1.1.2.1 =
* Changed author URL address

= 1.1.2 =
* Removed shadow from pagination to have a consistent look for dark layouts

= 1.1.1 =
* Administration UI improvements
* Added pause when hovering on pagination
* Added title size as some themes don't have proper heading styles
* Added screenshots for WordPress plugin repository

= 1.1 =
* Added pagination
* Fixed official homepage link
* Fixed the jQuery function (faster and cleaner)
* Removed an unused .js file

= 1.0 =
* First release
