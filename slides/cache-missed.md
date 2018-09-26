##  cache missed

![](resources/images/request-stack-with-caching.png) <!-- .element: class="plain" style="width: 750px;" -->

note:
    The request is uncached, and is running the full stack of code, to build the next page. So the server is back to working hard. (This could also be the result of a logged in user request, which bypasses the page cache.)
