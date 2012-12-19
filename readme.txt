=== Twenty Twelve Schema.org Child Theme  ===
Contributors: uplink

A child theme for the standard WordPress Twenty Eleven theme that integrates Schema.org microdata directly into each page.

== Description ==

The default WordPress Twenty Twelve theme is beautiful and functional. I wanted to make it even more functional by including added microdata in the theme by default. Google, along with several other large companies like Bing and Yahoo, introduced Schema.org, a collection of microdata formats that can be used as a common machine language to identify bits and pieces of web pages. This theme incorporates that language and embeds it directly into your site.

For example, each post now is wrapped with `<article itemscope itemtype="http://schema.org/BlogPosting">`, and contains other relevant markup such as `<h1 itemprop="headline">A blog post</h1>` and `<div itemprop="articleBody"> ... Entry goes here ... </div>`. 

Adding microdata to your site has several benefits. First and foremost, you contribute to machine readable data everywhere. The Internet is a wonderful place for humans to browse, but we can make it more accessible and more consumable if we let the computer figure as much of it out as it can. Second, search engines can use this data to get a better understanding of each page that it indexes, and hopefully provide more relevant search results. **(Notice that I am not saying you are going to get an SEO boost for doing this. You may, you may not, I have no idea. But if everyone included this data on their sites, the results would be better.)** There are no downsides really to simply plugging the data in.

Additionally, I have added a three widget section to the footer, since that functionality existed in Twenty Eleven and was very useful. The widgets in the footer are optional, but available for use.

== Frequently Asked Questions ==

= Are there ways to modify the markup that is inserted? =

I have been careful to only insert rather generic markup into the theme, so it should apply rather well to any situation. That being said, you will want to edit the theme files directly in order to make changes.

= Will this give me an awesome SEO boost? =

No idea. I highly doubt it. But you will be contributing to machine readable data on the Internet, and Google at least will be able to parse your rich microdata!

== Changelog ==

*Note: The theme version is designed to track the Twenty Twelve theme version for x.y releases. Third point releases (x.y.z) are updates made apart from Twenty Twelve parent theme releases.*

= 1.0 =
* Initial release
= 1.1.1 =
* Match the official 1.1.1 version, released with WP 3.5
= 1.1.2 =
* Fix for typo in functions.php to allow Schema.org markup in posts. 