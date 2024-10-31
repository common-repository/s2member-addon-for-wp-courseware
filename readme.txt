=== WP Courseware for S2Member ===
Contributors: flyplugins
Donate link: https://flyplugins.com/donate
Tags: learning management system, selling online courses
Requires at least: 4.8
Tested up to: 6.2.2
Stable tag: 1.1
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html

This plugin adds integration between S2Member and WP Courseware which allows you to associate courses to membership levels for automatic enrollment.

== Description ==
[Fly Plugins](https://flyplugins.com) presents [S2Member](https://s2member.com/) for [WP Courseware](https://flyplugins.com/wp-courseware).

= Would you like to sell an online course with S2Member? =
The S2Member Addon for WP Courseware will add full integration with WP Courseware. Simply assign WP Courseware courses to an S2Member membership level. When a student purchases the membership level, they will automatically be enrolled into the associated courses.

With this addon, you will be able to create a fully automated [Learning Management System](https://flyplugins.com/wp-courseware) and sell online courses.

= S2 Membership Plugin Integration with WP Courseware =
[youtube https://www.youtube.com/watch?v=HC0IMrLZuLU]

= Basic Configuration Steps =
1. Create a course with WP Courseware and add modules, units, and quizzes
2. Create a course outline page using [shortcode]
3. Create a membership level and set a price
4. Associate one or more WP Courseware courses with the membership level
5. New student pays for the membership level, and WP Courseware enrolls them to the appropriate courses based on the purchased membership level

= Check out Fly Plugins =
For more tools and resources for selling online courses check out:

* [WP Courseware](https://flyplugins.com/wp-courseware/) - The leading learning management system for WordPress. Create and sell online courses with a drag and drop interface. It’s that easy!
* [S3 Media Maestro](https://flyplugins.com/s3-media-maestro) - The most secure HTML 5 media player plugin for WordPress with full AWS (Amazon Web Services) S3 and CloudFront integration.

= Follow Fly Plugins =
* [Facebook](https://facebook.com/flyplugins)
* [YouTube](https://www.youtube.com/flyplugins)
* [Twitter](https://twitter.com/flyplugins)
* [Instagram](https://www.instagram.com/flyplugins/)
* [LinkedIn](https://www.linkedin.com/company/flyplugins)

= Disclaimer =
This plugin is only the integration, or “middle-man” between WP Courseware and s2Member.

== Installation ==

1. Upload the `S2 Member addon for WP Courseware` folder into the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently asked questions ==

= Does this plugin require WP Courseware to already be installed =

Yes!

= Does this plugin require S2Member to already be installed =

Yes!

= Where can I get WP Courseware? =

[WP Courseware](https://flyplugins.com/wp-courseware)

= Where can I get S2Member? =

[S2Member](https://flyplugins.com/s2member).

== Screenshots ==

1. The Course Access Settings screen will display the courses associated with membership levels

2. This is the screen where specific courses are selected to be associated with the membership level. The retroactive function will enroll students to courses that were recently associated to the membership level.

== Changelog ==

= 1.1 =
* New: Added function to retroactively assign new courses to existing membership levels that have already been purchased
* Tweak: Added a database clean up function to rename the level IDs in the wpcw_member_level table
* Tweak: Changed level ID naming scheme from s2member_x to s2member_level(x) to match role name

= 1.0 =
* Initial release


== Upgrade notice ==

