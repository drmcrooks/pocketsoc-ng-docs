# Exercise 4: Generate some traffic

The traffic you can see already is background - DNS requests, etc. We now want to generate some traffic of our own that we can identify

1. In a Portainer tab, look for the client container and open a terminal
2. Do a simple `curl` command to download a "payload" from our webserver
```
curl http://webserver -o payload
```
3. Let's get some information about this file - in particular, it's contents...
```
cat payload
```
4.  ... and MD5 checksum. 
```
md5sum payload
```
5. This forms an extremely simple analysis, but gives us enough to go back to the Dashboards tab