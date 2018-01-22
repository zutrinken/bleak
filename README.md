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
* Disqus/Gitalk support
* Subscribers support
* Sharing buttons

## Setup

To enable [Disqus](https://disqus.com/) comments go to your blogs code injection settings and add `<script>var disqus="YOUR_DISQUS_SHORTNAME";</script>` to your blog header. You can also try [Gitalk](https://github.com/gitalk/gitalk), a comment system based on Github Issue. Just need insert its dependencies and config to the blogs code injection.

```
<link rel="stylesheet" href="https://unpkg.com/gitalk/dist/gitalk.css">
<script src="https://unpkg.com/gitalk/dist/gitalk.min.js"></script>
<script>
var gitalkConf = {
  clientID: 'YOUR_GITHUB_APP_CLIENTID',
  clientSecret: 'YOUR_GITHUB_APP_CLIENTSECRET',
  repo: 'YOUR_GITHUB_REPO',
  owner: 'YOUR_GITHUB_ACCOUNT',
  admin: ['YOUR_GITHUB_ACCOUNT'],
  // facebook-like distraction free mode
  distractionFreeMode: false
};
</script>
```

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

Copyright (C) 2015-2017 Peter Amende - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
