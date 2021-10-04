# Caching User Information

**Redis** is an open source (BSD licensed), in-memory data structure store, used as a database, cache, and message broker. Redis provides data structures such as strings, hashes, lists, sets, sorted sets with range queries, bitmaps, hyperloglogs, geospatial indexes, and streams.

## Description
This program can show a user on github has how many public repositories by specify username in URL. Load user information as __key-pair values__, read in-memory data via redis caching can speedy up loading time a lot.  

### Runing program locally 
`npm start`

### Redis CLI
`redis-cli`
```
127.0.0.1:6379> get YolandaDuan
"26"
```



