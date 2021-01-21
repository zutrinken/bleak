# Bleak

An elegant AJAX driven theme for [Ghost](https://github.com/tryghost/ghost/). See a demo at: [bleak.peteramende.de](https://bleak.peteramende.de/)

If you like this theme, you can buy me a ~~coffee~~ [beer](https://paypal.me/zutrinken).

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

## ⭐️Features

* Responsive layout
* Automatic code syntax highlight and line numbers
* Disqus support

## 🎨 Setup custom color

1. Go to __Code injection__.  
2. Add this to __Blog Header__:  
````
<style>
  :root {
    --color-primary: #D95736;
    --color-primary-active: #BF4526;
  }
</style>
````

## 💬 Setup [Disqus](https://disqus.com/)


1. Go to __Code injection__.  
2. Add this to __Blog Header__:  
````
<script>var disqus = 'YOUR_DISQUS_SHORTNAME';</script>
````

## Sticky Header

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

Copyright (C) 2015-2021 Peter Amende - Released under the [MIT License](https://github.com/zutrinken/bleak/blob/master/LICENSE).
