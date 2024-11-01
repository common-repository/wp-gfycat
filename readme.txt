=== WP Gfycat ===
Contributors: leogg
Tags: gfycat,shortcode,video,image,gif,html5
Donate link: http://labs.monchito.net/wp-gfycat/
Requires at least: 3.9.1
Tested up to: 4.9.8
Stable tag: 0.9.3
License: GPLv2 or later
License URI: http://www.gnu.org/copyleft/gpl.html

A simple shortcode to add your gfycat videos into your website. 

== Description ==
A simple shortcode to add your gfycat videos into your website. This plugin will enable you to use shortcodes to insert your gfycat videos from gfycat.com. Based on [gfycat.js](https://github.com/gfycat/gfycat.js), an embed script to generate gfycat embeds on 3rd party websites by gfycat.com.

= WP Gfycat options =

* `data_id`: the gfycat id (required)

= Basic example =

Add Gfycat in your post, page or widget:

`[gfycat data_id="BestYellowishElephantseal"]`

== Installation ==
Automatic Installation

1. Download the current version of the WP Gfycat plugin.
1. Go to your WordPress Admin Panel and click on Plugins >> Add New >> Upload
1. Choose the downloaded package and Install and Activate the WP Gfycat plugin.

Manual Installation

1. Download the current version of the WP Gfycat plugin.
1. Unzip the fileand upload the wp-gfycat folder into the /wp-content/plugins directory of your WordPress installation.
1. Go to your Admin panel and activate the WP Gfycat plugin.

== Frequently Asked Questions ==

= How do I embed gfycats in my posts/pages/templates? =

1. Copy and paste the ID of a gfycat video anywhere in your posts or pages. (The ID is the part after http://gfycat.com/ in the URL. E.g. **MelodicShadowyChinchilla** in http://gfycat.com/MelodicShadowyChinchilla)
1. Select the text you just pasted and click the WP Gfycat button in the visual editor.
1. That's it! Save your post or preview it.

You can enter manually the `[gfycat]` shortcode anywhere in your posts, pages or widgets:

`[gfycat data_id="BestYellowishElephantseal"]`

You can also display the gfycats outside your posts or pages using `do_shortcode`:

`<?php echo do_shortcode('[gfycat data_id="BestYellowishElephantseal"]'); ?>`

== Screenshots ==

1. Copy and paste the gfycat ID in your post or page.
2. Highlight the ID.
3. Click on the wp-gfycat button to insert the shortcode.
4. That's it! Preview the draft or publish your post to see the results.

== Changelog ==
= 0.9.3 =
* Switched to new API endpoint.
* Now uses iframes for displaying Gfys.
= 0.9.2 =
* Now you can insert the shortcode in your widgets.
= 0.9.1 =
* Added a wp-gfycat button to the TinyMCE editor.
= 0.9 =
* Initial release.
