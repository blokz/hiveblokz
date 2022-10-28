# hiveblokz
add a hive.io blockchain users most recent posts to any website.

# usage:
```
<div id="hiveblokz"></div>
<script
 hiveuser="sn0n" 
 frontend="leofinance.io" 
 apinode="api.hive.blog" 
 src="https://blokz.github.io/hiveblokz/hiveblokz.js" 
 type="text/javascript"></script>
```

# options
`hiveuser` is required

`frontend` is optional and defaults to https://personal.community/
any frontend that uses the domain/@hiveuser is valid, i.e. peakd, hive.blog, leofinance.io, ecency

`apinode` is optional and defaults to https://api.deathwing.me/


when manually setting `apinode` or `frontend`, omit the `https://` as the script will add that automagically.
 
