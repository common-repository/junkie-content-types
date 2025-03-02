=== Junkie Types ===
Contributors: themejunkie
Tags: custom post type, post type, slider, service, team, testimonial, doctor, department, feature
Requires at least: 4.6
Tested up to: 6.1
Stable tag: 1.1.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

The All-in-one custom post types to extend themes.

== Description ==

**Please note this plugin is still in beta version**

With small code in your themes, you can enable several custom post types you need. The idea behind this plugin is to extend our themes at Theme Junkie, but you can enable it in all themes. Every post types comes with custom meta boxes and some with custom taxonomy.

= Post Types Included =

* Team
* Testimonial
* Doctor
* Department
* Service
* Feature
* Slider

= TO DO =
* Shortcodes
* Widgets
* Portfolio post type

== Installation ==

**Through Dashboard**

1. Log in to your WordPress admin panel and go to Plugins -> Add New
2. Type **junkie types** in the search box and click on search button.
3. Find Junkie Types plugin.
4. Then click on Install Now after that activate the plugin.

**Installing Via FTP**

1. Download the plugin to your hardisk.
2. Unzip.
3. Upload the **junkie-types** folder into your plugins directory.
4. Log in to your WordPress admin panel and click the Plugins menu.
5. Then activate the plugin.

== Frequently Asked Questions ==

= How to enable the post type? =
Add this line in your theme `functions.php`.
`
// Enable Team post type.
add_theme_support( 'junkie-team' );

// Enable Testimonial post type.
add_theme_support( 'junkie-testimonial' );

// Enable Doctor post type.
add_theme_support( 'junkie-doctor' );

// Enable Department post type.
add_theme_support( 'junkie-department' );

// Enable Feature post type.
add_theme_support( 'junkie-feature' );

// Enable Service post type.
add_theme_support( 'junkie-service' );

// Enable Slider post type.
add_theme_support( 'junkie-slider' );
`

== Changelog ==

= 1.1.4 - 06/12/2015 =
* Add **Role** metabox to the testimonial post type.

= 1.1.3 - 05/07/2015 =
* Add 'excerpt' support to Department, Doctor, Feature, Service and Team post type
* Change the priority of Doctor and Team metaboxes, since it should appear below the excerpt

= 1.1.2 - 04/24/2015 =
* Revert the post types name.

= 1.1.1 - 04/23/2015 =
* Rename all post types
* Improve Doctors post type metaboxes
* Change 'department' taxonomy to 'speciality'

= 1.1.0 - 04/23/2015 =
* Add `flush_rewrite_rules()` function to remove rewrite rules and then recreate rewrite rules
* Fix 'Team' post type metaboxes couldn't be save the value

= 1.0.0 - 04/21/2015 = 
* Initial release.