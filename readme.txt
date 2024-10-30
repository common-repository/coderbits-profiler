=== Coderbits Profiler ===
Contributors: dev_HE
Donate link: 
Tags: coderbits, json, data, aggregate, widget
Author URI: http://coderbits.com/stefanbc
Requires at least: 3.3
Tested up to: 3.8.1
Stable tag: 1.2.7
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Display Coderbits profile data as widget or using a shortcode

== Description ==

Display your Coderbits profile data using a widget or a shortcode.

This plugin is using the provided Coderbits API that can be accesed [here](http://coderbits.com/api).

To use the shortcode functionality just call `[coderbits data="TYPE_OF_DATA"]` in a page or post.

**Types of data:**

name, title, bio, location, website_link, views, rank, gravatar_hash, badges_count, follower_count, following_count, top_skills, top_languages, top_environments, top_frameworks, top_tools, top_interests, top_traits, top_areas, badges, accounts

== Installation ==

1. Place the `coderbits-profiler` folder in your `/wp-content/plugins/` directory.
2. Give the cache folder write permissions. Usually `chmod(777)`.
3. Activate the `Coderbits Profiler` plugin.
4. Visit `Settings` and adjust your configuration.
5. Add the `Coderbits Profiler` widget to your website.
6. **(Optional)** Add the `Coderbits Profiler` shortcode `[coderbits-profiler data="TYPE_OF_DATA"]` to a page or post
7. View your site.
8. Adjust the CSS of your theme as needed, to make everything pretty.

== Screenshots ==

1. Main plugin view

== Changelog ==

= Version 1.2.7 =

* Fixed issue [#18](https://github.com/stefanbc/Coderbits-Profiler/issues/18)

* Works with WordPress 3.8.1

= Version 1.2.6 =
* Works on WordPress 3.8 and small UI changes

= Version 1.2.5 =
* Minor update that fixes the badges output

= Version 1.2.4 =
* Fixed broken image link for some services when using shortcode

= Version 1.2.3 =
* Fixed issue [#15](https://github.com/stefanbc/Coderbits-Profiler/issues/15)
* Fixed issue [#16](https://github.com/stefanbc/Coderbits-Profiler/issues/16)

= Version 1.2.2 =
* Fixed issue [#12](https://github.com/stefanbc/Coderbits-Profiler/issues/12)
* Fixed issue [#13](https://github.com/stefanbc/Coderbits-Profiler/issues/13)

= Version 1.2.1 =
* Fixed issue [#9](https://github.com/stefanbc/Coderbits-Profiler/issues/9)

= Version 1.2 =
* Implemented shortcode