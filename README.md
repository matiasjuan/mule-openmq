OpenMQ example
====

This example is based on the WebSphere MQ Example that comes with Studio (http://www.mulesoft.org/documentation/display/current/WebSphere+MQ+Example).

It was modified to use Open MQ using this documentation http://www.mulesoft.org/documentation/display/current/Open+MQ+Integration.


Open MQ
----

Links:

*  Download binaries (no installer) for Unix (e.g. Mac OSX): https://mq.java.net/4.5.html
*  Documentation: http://download.oracle.com/docs/cd/E18930_01/index.htm
*  Admin guide: http://docs.oracle.com/cd/E18930_01/html/821-2438/aeodo.html#scrolltoc


Start:
```
cd bin
./imqbrokerd
```

Query broker status and params:
```
cd bin
./imqcmd query bkr -u admin
```
