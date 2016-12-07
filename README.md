# confedit

Highly portable command line tool for editing config files from scripts. Inspired by ```augtool```, ```uci``` and ```reg```

## Goals

* Highly portable
  * Works on Linux, \*BSD, etc.
  * "Sideloadable" via ssh, adb, serial terminal, rubber ducky, etc.
  * Works on emmbedded systems like router with ```busybox```
* Supports different config files
  * XML
  * JSON
  * ini
  * "key = value"
* Support different operation
  * set
  * reset
  * set value
  * add value
  * remove value
  * verify
  * read value
  
  
