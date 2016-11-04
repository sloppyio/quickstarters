# Wordpress

The official [wordpress](https://hub.docker.com/_/wordpress/) and [mysql](https://hub.docker.com/_/mysql/) image combined for a [sloppy.io](https://sloppy.io) project. You can extend the json/yml with more variables from the official images.

## Start it

```
sloppy start -var=USERNAME:username -var=URI:mydomain.sloppy.zone -var=DBUSER:db-user-for-wordpress -var=DBPASS:db-password-for-wordpress -var=DBROOT:db-root-password wordpress.json 

Example:

sloppy start -var=URI:mywordpress.sloppy.zone -var=DBUSER:wpadmin -var=DBPASS:secret -var=DBROOT:moresecret wordpress.json 
```