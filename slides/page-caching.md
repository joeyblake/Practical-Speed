##  page caching

![](resources/images/request-stack-with-page-caching.png) <!-- .element: class="plain" style="width: 800px; background: none;" -->

note:
    The goal here is to take a bunch of work out of the equation. If we capture the output of the page in a static form, and refresh it periodically, performance can dramatically improve because we’re not asking the server to do all of the work on every request.
