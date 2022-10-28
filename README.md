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

You can download the .js file and self host if you prefer to not use github.io as a CDN of sorts, just update the path to where you have it uploaded.

# options
`hiveuser` is required

`frontend` is optional and defaults to https://personal.community/
any frontend that uses the domain/@hiveuser is valid, i.e. peakd, hive.blog, leofinance.io, ecency

`apinode` is optional and defaults to https://api.deathwing.me/

A list of public API nodes can be found [here](https://developers.hive.io/quickstart/hive_full_nodes.html)




when manually setting `apinode` or `frontend`, omit the `https://` as the script will add that automagically.
 
# Todo 
Remove separator - undecided on how to present the post title and posted on date in a manner that will be presentable without additional CSS as I would like to remain as neutral as possible. currently using a blokz icon as a divider, which isn't optimal.. 
