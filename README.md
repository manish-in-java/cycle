jQuery Cycle Plugin
===================

This is a fork of the [jQuery Cycle](https://github.com/malsup/cycle) plugin by [Mike Alsup](https://github.com/malsup). This fork was started to address bugs in the plugin and to make additions after development on the original plugin stopped after July 2013.

This fork contains the following additions/changes to the last version of the original plugin released in July 2013:

1. *Better container resizing*: the plugin adds CSS classes to set the width and height of the slide container to match the dimensions of the largest slide. The width and height of slides are calculated without taking their margins into consideration. This mechanism works most of the times but distorts the slides in some odd cases, especially when `box-sizing` is set to `border-box` for the slides. Passing `widthIncludesMargin : true` and `heightIncludesMargin : true` when initialising the plugin forces it to take the margins into consideration when calculating the slide width and height, respectively. The default values of `widthIncludesMargin` and `heightIncludesMargin` are set to `false` to retain the plugin's default behaviour.
1. *Slideshow does not resume on mouseout with the Lite version*

----

Cycle is an easy-to-use slideshow plugin that provides many options and effects for creating beautiful slideshows.

Links

* [Home Page](http://jquery.malsup.com/cycle/)
* [Options Reference](http://jquery.malsup.com/cycle/options.html)
* [Effects Browser](http://jquery.malsup.com/cycle/browser.html)
* [Download](http://jquery.malsup.com/cycle/download.html)
 
