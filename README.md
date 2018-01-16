# Scheduled Featured Images #

[![Join the chat at https://gitter.im/ndigitals/scheduled-featured-images](https://badges.gitter.im/ndigitals/scheduled-featured-images.svg)](https://gitter.im/ndigitals/scheduled-featured-images?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![GitHub (pre-)release](https://img.shields.io/github/release/ndigitals/nds-wp-scheduled-featured-images/all.svg?style=flat-square)](https://github.com/ndigitals/nds-wp-scheduled-featured-images.git)
[![WordPress](https://img.shields.io/wordpress/v/nds-wp-scheduled-featured-images.svg?style=flat-square)]()
[![Maintenance](https://img.shields.io/maintenance/yes/2017.svg?style=flat-square)]()
[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg?style=flat-square)](LICENSE.md)

**Contributors:** [tnolte](https://profiles.wordpress.org/tnolte), [ndigitals](https://profiles.wordpress.org/ndigitals)  
**Author:** Nolte Digital Solutions  
**Author URI:** https://www.ndigitals.com/  
**Plugin URI:** https://www.ndigitals.com/wordpress/plugins/scheduled-featured-images-plugin/  
**Donate link:** https://www.ndigitals.com/donate/  
**Tags:** images, featured, nds, schedule  
**Requires at least:** 4.4  
**Tested up to:** 4.8.2  
**Requires PHP:** 5.5.9  
**Stable tag:** 1.0  
**License:** GPLv2 or later  
**License URI:** https://www.gnu.org/licenses/gpl-2.0.html  

Scheduled Featured Images allows you to attach multiple images to any post-type and set them to be the featured image based on a schedule.

## Description ##

The idea for this plugin was born out of the need to more easily manage a website that had it's Front Page updated with a new weekly/monthly/etc featured image. The Front Page, and other site Pages, featured image was planned out ahead of time, sometimes for months in advance, so it seemed tedious to have to manually update the featured images whenever they would change. Since the website's theme used the standard WordPress Featured Image functionality, to manage the header/banner image on each page, it seemed to make the most sense to expand on that and provide a way to manage future featured images.

## Features ##

* Attach Multiple Featured Images to Any Post Type
 * Scheduled Start and End Date/Time
 * Overlapping Schedules
 * Blank Schedules
* Fallback Options to Allow For Overrides & Defaults
* User Roles & Permissions
 * Restrict Who Can Set Per-Post Type Overrides

## Progress & Development ##
[![Travis](https://img.shields.io/travis/ndigitals/nds-wp-scheduled-featured-images.svg?style=flat-square)](https://travis-ci.org/ndigitals/nds-wp-scheduled-featured-images)

* [Roadmap](https://trello.com/b/8mT9hQWj) - Trello
* [Source Code Repository](https://github.com/ndigitals/nds-wp-scheduled-featured-images) - GitHub
* [Known Issues](https://github.com/ndigitals/nds-wp-scheduled-featured-images/issues) - GitHub

## Installation ##

1. Upload the `nds-wp-scheduled-featured-images` plugin to the `/wp-content/plugins/` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin.
1. Configure the plugin via `Settings->Featured Images` to meet your site's needs.

If you have any troubles please [contact us](https://www.ndigitals.com/contact/).

## Frequently Asked Questions ##

### What will happen to my post-type's existing featured images after I enable the plugin? ###

Until the plugin's global settings, `Settings->Featured Images`, are updated to change it's behavior, your existing feature images will remain unchanged.

### What will happen to my post-type's featured images if I disable the plugin? ###

Whatever is the currently set/displayed featured image will remain as the current featured image.
## Screenshots ##

1. Plugin settings.
2. Plugin post-type metabox.

## Changelog ##

### 1.0.0 ###
* First public release!

