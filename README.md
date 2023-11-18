# TairGis
TairGis is a Redis Module that supports the query of intersection, contains, and within relationships between points, lines, and polygons

compile base on source code https://github.com/tair-opensource/TairGis

# Run

## Solution 1:
  add parameters to redis.conf
  
  enable-module-command yes
  
  loadmodule tairgis.dll
## Solution 2:

  redis-server.exe --loadmodule tairgis.dll
  
