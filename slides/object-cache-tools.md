##  object cache tools

*Require Memcached or Redis to be installed on your server

* [WP Redis](https://wordpress.org/plugins/wp-redis/)
* [WP Memcached](https://github.com/Automattic/wp-memcached)

note:
    This will take load off of the database as queries are run and certain data in a query is automatically cached in the persistent data store, just by having object caching enabled.

    Talk about WordPress Object cache
    Talk about WP Query caching
    Talk about transients

    Employing these things will get you a long way on your quest for speed. They don’t require loads of of dev time, and they set up your site platform to allow more performance enhancements down the road. These are broad strokes that will improve performance of your site, and are the most practical first steps.
