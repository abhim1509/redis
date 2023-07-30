# redis

brew install redis

redis server

set city "Hyd"

get city

EXISTS city

set city  "Chd" - Overrided the previous key, stores uniquely.
del city  Commands can be written upper and lower case.



To store objects (earlier version)
 redis.set(JSON.stringfy(obj))
 redis.get(JSON.parse(obj))


 New command:
 JSON.set animal $ '"dog"'
