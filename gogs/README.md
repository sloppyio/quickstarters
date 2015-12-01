# Gogs

Gogs - Go Git Service https://gogs.io/

## Start it

```
sloppy start gogs.json  -var=URI:mydomain.sloppy.zone
   
Example:
   
sloppy start gogs.json  -var=URI:mygogs.sloppy.zone
```

On the setup page choose sqlite as database and change Application-URL to the .sloppy.zone subdomain (for example http://mygogs.sloppy.zone) you choosed. As sloppy.io does not support TCP ports for exposing in the public version you can not use SSH for git commands.