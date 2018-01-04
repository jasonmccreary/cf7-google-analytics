=== Contact Form 7 Google Analytics ===
Contributors: macbookandrew
Tags: contact form, contact form 7, cf7, contactform7, google analytics, ga, universal, forms, form, track, tracking, event, events, goal, goals
Donate link: https://cash.me/$AndrewRMinionDesign
Requires at least: 4.3
Tested up to: 4.8
Stable tag: 1.6.1
License: GPL2

Adds Google Analytics Event Tracking to all Contact Form 7 forms.

== Description ==
Adds Google Analytics Event Tracking to all Contact Form 7 forms sitewide, using “Contact Form” as the Event Category, “Send” as the Event Action, and the form name as the Event Label.

Supports the most popular Google Analytics plugins, including the following:

- [Google Analytics by MonsterInsights](https://wordpress.org/plugins/google-analytics-for-wordpress/), formerly “Google Analytics by Yoast”
- [Google Analytics Dashboard for WP](https://wordpress.org/plugins/google-analytics-dashboard-for-wp/) by Alin Marcu
- [Google Analytics](https://wordpress.org/plugins/googleanalytics/) by Kevin Sylvestre
- [Google Analytics](https://wordpress.org/plugins/pc-google-analytics/) by Praveen Chauhan
- [Analytics Tracker](https://wordpress.org/plugins/analytics-tracker/) by Valeriu Tihai
- The default Google Analytics code copied from the Analytics admin panel (both the newer `gtag.js` and the older universal `analytics.js`)
- Google Tag Manager (using `gtm.js`)
- Any other plugin using `gtag`, `ga`, `_gaq`, or `__gaTracker` as the Javascript function
- To add others, [open a pull request](https://github.com/macbookandrew/cf7-google-analytics)

== Installation ==
1. Install and activate the plugin
1. Enjoy!

== Frequently-Asked Questions ==

= Where will events show up? =

Check your statistics in Google Analytics under *Behavior > Events* or under *Real-Time > Events*

= How do I set a goal in Google Analytics? =

1. Click on “Admin” in your Google Analytics account menubar
1. In the right-most column (“View”), click on “Goals”
1. Click on the “+ New Goal” button
1. Choose the “Template” radio button (selected by default) and click “Continue”
1. Enter a name for the goal (I suggest “Contact Forms”)
1. Choose the “Event” radio button and click “Continue”
1. Set “Category Equals to Contact Form”
1. Set “Action Equals to Sent”
1. Optionally add a label if you want to define a goal for one specific form
1. Click the “Save” button


== Changelog ==

= 1.6.1 =
 - Add support for PHP < 5.3

= 1.6.0 =
 - Add support for Google Tag Manager

= 1.5.0 =
 - Add support for sending the Contact Form 7 form name instead of just the form ID

= 1.4.1 =
 - Update suppoprt for gtag.js custom events

= 1.4.0 =
 - Add support for the Global Site Tag (gtag.js)

= 1.3.0 =
 - Update to use new DOM events in Contact Form 7 v4.8

= 1.2.2 =
 - Fix JS issue if `ga` is undefined

= 1.2.1 =
 - Fix PHP undefined index issue

= 1.2 =
 - Fix issue where any manually-specified items were being deleted

= 1.1 =
 - Add support for Google Analytics by Yoast

= 1.0 =
 - First stable version
