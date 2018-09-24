##  object caching - level 2

Leveraging object caching in your custom code.

```
function get_my_custom_data( $param ) {
    $cache_key = 'my_custom_data_' . $param;
    $custom_data = get_transient( $cache_key );
    if ( false === $custom_data ) {
        $custom_query = new WP_Query([...]);
        $custom_data = $custom_query->posts;
        set_transient( $cache_key, $custom_data, 'my_group', 5 * 60 );
    }
    return $custom_data;
}
```

note:
    Talk about WP Query caching
    Talk about transients

    Don't cache the whole query

    Employing these things will get you a long way on your quest for speed. They don’t require loads of of dev time, and they set up your site platform to allow more performance enhancements down the road. These are broad strokes that will improve performance of your site, and are the most practical first steps.
