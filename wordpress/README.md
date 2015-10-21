# Wordpress

The official [wordpress](https://hub.docker.com/_/wordpress/) and [mysql](https://hub.docker.com/_/mysql/) image combined for a [sloppy.io](http://sloppy.io) project. You can extend the json with more variables from the official images.

## Start it

```
sloppy start wordpress.json  -var=USERNAME:username,URI:mydomain.sloppy.zone,DBUSER:db-user-for-wordpress,DBPASS:db-password-for-wordpress,DBROOT:db-root-password
where USERNAME has to be your  sloppy.io username
Example:

sloppy start wordpress.json  -var=USERNAME:john,URI:mywordpress.sloppy.zone,DBUSER:wpadmin,DBPASS:secret,DBROOT:moresecret
```