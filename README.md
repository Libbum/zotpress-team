# zotpress-team

Fork of ZotPress, for use when you also want a group publication list.

=== Zotpress ===
Contributors: kseaborn
Plugin Name: Zotpress
Plugin URI: http://katieseaborn.com/plugins/
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=5HQ8FXAXS9MUQ
Tags: zotero, zotpress, citation manager, citations, citation, cite, citing, bibliography, bibliographies, reference, referencing, references, reference list, reference manager, academic, academic blogging, academia, scholar, scholarly, scholarly blogging, cv, curriculum vitae, resume, publish, publication, publications
Author URI: http://katieseaborn.com/
Author: Katie Seaborn
Requires at least: 3.5
Tested up to: 5.2.3
Stable tag: 7.1.5
License: Apache2.0

Zotpress displays your Zotero citations on WordPress.

== Description ==

[Zotpress](http://katieseaborn.com/plugins/ "Zotpress for WordPress") brings publication broadcasting and scholarly blogging to WordPress through [Zotero](http://zotero.org/ "Zotero"), a free, cross-platform reference manager.

= Features =
* Displays your personal and group Zotero items through in-text citations, bibliographies, and searchable libraries
* Supports thumbnail images through WordPress's Media Library and Open Library
* Supports selective CSS styling via IDs and classes
* Provides a range of additional features, such as allowing visitors to download citations
* And more!

Compatible with Firefox, Safari, Chrome, and IE9. Made with jQuery, jQuery UI, jQuery doTimeout, Live Query, OAuth, and [Open Library](https://openlibrary.org/ "Open Library").

Special thanks to Joe Alberts for substantial contributions to the code, comprehensive testing, and design ideation. Thanks also to contributors Christopher Cheung and Jason S. for their development support and advice. Finally, my sincere gratitude goes out to all who have donated in support of this plugin.

= Requirements =
jQuery included in your theme (Zotpress will do this for you if it isn't already included), and an HTTP request method supported by WordPress enabled on your server: cURL, fopen with Streams (PHP 5), or fsockopen. In your server config file, X-Frame-Options should be set to SAMEORIGIN. Optional: OAuth enabled on your server.

== Installation ==

1. Install from the `Plugins` page in your WordPress admin panel. Or, download and extract the zip, then manually upload the folder `zotpress` to the `/wp-content/plugins/` directory.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. Go to the `Zotpress` page through the admin menu.
1. Add the Zotero API information for each Zotero account you'd like to use.
1. On the `Browse` page, look up the keys of the items, collections, or tags that you wish to display. Or, use the Zotpress Reference Widget to generate shortcodes.
1. Place the shortcodes in your blog post or page, or enable the Zotpress sidebar widget. Below are a few examples to get you started. Look at the `Help` page for more examples and the full details about all use options and shortcodes.

= Shortcode =
You can display your Zotero citations in a number of ways. To display a list of five citations from the collection with the key "ZKDTKM3X", use this shortcode:

> [zotpress collection="ZKDTKM3X" limit="5"]

You can also use in-text citations as follows:

> [zotpressInText item="{U9Z5JTKC,36-45}"]

> [zotpressInTextBib]

The first shortcode will display an in-text citation for an item with the key "U9Z5JTKC", which will look something like this: (Seaborn, 2011, p. 36). The [zotpressInTextBib] will auto-generate a bibliography for all [zotpressInText] shortcodes on the post/page.

Check out the "Help" page on your installation of Zotpress for more information and a full listing of parameters for all shortcodes.

== Frequently Asked Questions ==

The F.A.Q. can be found on the "Help" page of every Zotpress installation. If you have a question that isn't answered there, feel free to post a message in the [forums](https://wordpress.org/support/plugin/zotpress "Zotpress forums on Wordpress.com").

== Screenshots ==

1. Display items from individual or group Zotero libraries on your WordPress website. Special characters are supported.
2. Search for items using the autocomplete feature. Generate shortcodes for bibliographies and in-text citations using the "Zotpress Reference" widget on edit screens.
3. Give your citation an image using WordPress's Media Library or Open Library.
4. Share your library through your website. Allow visitors to browse by collection or tag.
5. Allow visitors to search your library by item metadata or tag, or both.

== Upgrade Notice ==

= 6.2.4 =

Updates what kinds of metadata the "download" feature will look for and what's removed from the database on reset. Minor style updates.
