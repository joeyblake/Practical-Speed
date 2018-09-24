##  object cache tools

*Require Memcached or Redis to be installed on your server

* WP Redis -- wordpress.org/plugins/wp-redis/
* WP Memcached -- github.com/Automattic/wp-memcached

<br>
* These plugins start storing cached data in memory between requests
* Reduces the amount of work the database needs to do

note:
    This will take load off of the database as queries are run and certain data in a query is automatically cached in the persistent data store, just by having object caching enabled.

