# Gogs

Gogs - Go Git Service https://gogs.io/

## Start it

```
sloppy start -var=URI:mydomain.sloppy.zone gogs.json

Example:

sloppy start -var=URI:mygogs.sloppy.zone gogs.json
```

On the setup page choose sqlite as database and change Application-URL to the .sloppy.zone subdomain (for example https://mygogs.sloppy.zone) you choosed. As sloppy.io does not support TCP ports for exposing in the public version you can not use SSH for git commands.
