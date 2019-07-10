# Bleak

An elegant AJAX driven theme for [Ghost](https://github.com/tryghost/ghost/) by [Peter Amende](https://zutrinken.com/).

Demo: [bleak.zutrinken.com](https://bleak.zutrinken.com/)

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
* Automatic code syntax highlight and line numbers
* Disqus support

## Setup

To enable [Disqus](https://disqus.com/) comments go to your blogs code injection settings and add `<script>var disqus="YOUR_DISQUS_SHORTNAME";</script>` to your blog header.

You can make the navigation stick to the top by adding the following lines via code injection:

```
<style>
  #wrapper {
    padding-top: 4em;
  }
  #nav {
    position: fixed;
  }
</style>
```

## Development

Install [Grunt](http://gruntjs.com/getting-started/):

	npm install -g grunt-cli

Install Grunt modules:

	npm install

Install [Bower](https://bower.io):

	npm install -g bower

Install Bower components:

	bower install

Build Grunt project:

	grunt

Distribute Grunt project:

	grunt build

## Copyright & License

Copyright (C) 2015-2019 Peter Amende - Released under the [MIT License](https://github.com/zutrinken/bleak/blob/master/LICENSE).
