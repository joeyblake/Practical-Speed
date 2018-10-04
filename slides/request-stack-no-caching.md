
![](resources/images/request-stack-without-caching.png) <!-- .element: class="plain" style="background:none;" -->

note:
    On a typical host, you'll have WordPress, PHP, and a Database installed.

    With no caching on your site, each request hits the php and database layer, causing WordPress to have to gather all of the data and assets to be displayed in the requested page, assemble them, and return the requested page to the browser.

    This requires the server to do a lot of work, which could result in slower page response times, and issues responding to high traffic load.
