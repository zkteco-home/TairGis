# TairGis
TairGis is a Redis Module that supports the query of intersection, contains, and within relationships between points, lines, and polygons

# Run

## Solution 1:
  add parameters to redis.conf
  
  enable-module-command yes
  
  loadmodule tairgis.dll
## Solution 2:

  redis-server.exe --loadmodule tairgis.dll
  
