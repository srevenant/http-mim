# http-mim

This is an ancient script, mostly here for posterity.  I recommend using https://mitmproxy.org/ nowdays.


HTTP man in the middle.  For debugging purposes.  I have used this by having a load balancer forward to the MiM, and then it forwards onto the end service, allowing me to see full queries and responses both directions.

```
./http-mim 4000 localhost 5000 outlog
```
