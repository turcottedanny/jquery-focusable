jQuery Focusable Selector
=========================

Selector to find every focusable elements. Useful to find the first focusable element that can have 
the focus. I use this snippet a lot when building websites that need to be accessible.

Prerequisite
------------

Add jQuery to your project. 

Install
-------

Just add the content of jquery.focusable.js to your javascript files. Make sure jQuery is loaded before including this snippet.

Usage
-----

$('#my-container').find(':focusable');
