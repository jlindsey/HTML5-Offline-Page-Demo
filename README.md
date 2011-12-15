HTML5 Offline App Cache Demo
============================

Demonstrates displaying a custom page to the user when offline.

Demo
-----

Use a simple static webserver like [thin](http://code.macournoyer.com/thin/) or [pow](http://pow.cx). Navigate
to the index page to initialize the application cache. If you're in Chrome, you can see the app cache events firing
in the javascript console.

Now turn the webserver off and reload the page. You should be redirected to `/offline.html`, which is loading from the
local cache storage.

Turn the webserver back on and reload the browser once more. You should be redirected from `/offline.html` back to `/`.

License
-------

Code is licensed under WTFPLv2. See LICENSE for details.

