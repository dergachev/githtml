Fork Description
================
This repo (https://github.com/dergachev/githtml.git) was forked from https://github.com/ryt/githtml.git to illustrate an XSS vulnerability in the latter, as 
reported in https://github.com/ryt/githtml/issues/9

To try the potentially more secure version of githtml.js, add a bookmarklet using the following URL:


```javascript
javascript:(function(){var d=document,s=d.createElement('script');s.src='//raw.github.com/dergachev/githtml/master/githtml.js';d.body.appendChild(s);})();
```



For a diff of the code, see https://github.com/dergachev/githtml/compare/master

githtml
===========
> githtml is a utility that lets you view rendered HTML pages from github repositories on the fly.

<a href="http://ryt.github.com/githtml/">Install</a>
----------------------------------------------------
Install from http://ryt.github.com/githtml/

Old Install
-------
* Create a new bookmark in your bookmarks bar named `git-html`<br>
* Copy and paste the following code as the link or URL of the bookmark. 

```javascript
javascript:(function(){var d=document,s=d.createElement('script');s.src='//raw.github.com/ryt/githtml/master/githtml.min.js?2';d.body.appendChild(s);})();
```


Alternatively, if github allows you, you can drag 
<a href="javascript:(function(){var d=document,s=d.createElement('script');s.src='//raw.github.com/ryt/githtml/master/githtml.min.js?2';d.body.appendChild(s);})();" title="git-html">[this]</a> to your bookmarks bar.

Usage
=====
These are HTML pages from various repos.<br>
Browse them and click on the "git-html" bookmark to render them. 

Note: make sure you allow pop-ups from *.github.com in your browser.

> Note 2: This works best with Chrome or Safari. Firefox won't load js and css files for some of these links. Will fix soon.

* <a href="https://github.com/ryt/githtml/blob/master/example.html">Example Page</a>
* <a href="https://github.com/mrdoob/three.js/blob/master/examples/canvas_interactive_cubes_tween.html">Three.js 1</a>
* <a href="https://github.com/mrdoob/three.js/blob/master/examples/webgl_trackballcamera_earth.html">Three.js webgl earth</a>
* Bootstrap <a href="https://github.com/twitter/bootstrap/blob/master/docs/index.html">https://github.com/twitter/bootstrap/blob/master/docs/index.html</a>
* Backbone <a href="https://github.com/documentcloud/backbone/blob/master/examples/todos/index.html">https://github.com/documentcloud/backbone/blob/master/examples/todos/index.html</a>
* Gmaps <a href="https://github.com/HPNeo/gmaps/blob/master/examples/context_menu.html">https://github.com/HPNeo/gmaps/blob/master/examples/context_menu.html</a>