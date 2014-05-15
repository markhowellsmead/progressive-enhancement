Best practice template for progressive enhancement
==================================================

This page is intended to be a basic starting point for a template which implements best-case progressive enhancement principles. It is not a "design" per se, nor is it suitable for unmodified use in a production environment.

What is progressive enhancement?
--------------------------------

The principle is based on the concept of allowing all of your content to be accessible to all users. This sample page works excellently whether JavaScript is enabled or not; both with and without the use of @media-queries to allow responsive design to take effect.

The page, CSS and HTML works seamlessly on mobile devices, both large and small, and text readers. It works in older browsers and the very newest browsers. The newer and more capable the browser, the more advanced the experience.

What's the point?
-----------------

By applying these principles, you can more easily provide advanced styling and interaction to those visitors who can use them.

For example, delivering a menu using a Javascript function is pointless, if the browser doesn't understand (or allow) Javascript.

Delivering a load of CSS rules for a responsive layout to IE8 is pointless: this browser doesn't understand the basic @media{} rule which makes it all possible.

Steps
-----

* The basic page layout is delivered, with a simple stylesheet containing rules which all browsers can understand.
* If the browser has Javascript activated, the Javascript files are loaded using an inline Javascript function. So if the browser doesn't have Javascript capability, it won't even load the files.
* If the browser has Javascript activated, then additional CSS files are loaded which contain more advanced rules.
* By using the simple attribute media="(min-width:0)", the file containing CSS code for responsive layouts won't be loaded by browsers which don't understand these rules.
* This article and code was written by Mark Howells-Mead and most recently published on 15th May 2014.

Demo
----

A demonstration of the template in this is available at http://stuff.mhm.li/progressive-enhancement/.

Author
------

Mark Howells-Mead | http://mhm.li/

License
-------

All code within this repository is provided as-is under the GPL GNU General Public Licence v3 and may be freely used, adapted and built upon. No guarantee is provided or implied. See http://www.gnu.org/licenses/gpl.html for full terms of the license.

Please submit questions, tips, corrections and general excitement and praise via m@mhm.li. My online presence is linked from http://mhm.li/.