# Bleak

An elegant AJAX driven theme for [Ghost](http://github.com/tryghost/ghost/) by [Peter Amende](http://zutrinken.com/).

***

_**Hint:** This theme works with AJAX, so it won’t work with multiple domains properly! Use redirects to only one domain instead. Also make sure you haven’t jQuery injected in your footer due to [Ghosts migration method](http://dev.ghost.org/no-more-jquery/). This can break the layout!_

## Demo

* [Blog](http://bleak.zutrinken.com)
* [Post](http://bleak.zutrinken.com/demo)
* [Tags](http://bleak.zutrinken.com/tag/general)
* [Author](http://bleak.zutrinken.com/author/zutrinken)

## Screenshots

<table>
<tr>
<td valign="top">
<img src="https://raw.githubusercontent.com/zutrinken/bleak/master/src/screenshot-desktop.jpg" />
</td>
<td valign="top">
<img src="https://raw.githubusercontent.com/zutrinken/bleak/master/src/screenshot-mobile.jpg" />
</td>
</tr>
</table>

## Features

* Responsive layout
* Blog navigation
* Post navigation
* Cover images for blog, tag and author archives
* Featured posts style
* Automatic code syntax highlight and line numbers
* Disqus support
* Subscribers support
* Sharing buttons

## Setup

To enable [Disqus](https://disqus.com/) comments go to your blogs code injection settings and add `<script>var disqus="YOUR_DISQUS_SHORTNAME";</script>` to your blog header.

## Development

Install [Grunt](http://gruntjs.com/getting-started/):

	npm install -g grunt-cli

Install Grunt modules:

	npm install

Install [Bower](http://bower.io):

	npm install -g bower

Install Bower components:

	bower install

Build Grunt project:

	grunt

Distribute Grunt project:

	grunt build

## Copyright & License

Copyright (C) 2015-2018 Peter Amende - Released under the [MIT License](https://github.com/zutrinken/bleak/blob/master/LICENSE).
