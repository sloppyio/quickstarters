# PrestaShop

The official [PrestaShop](https://hub.docker.com/r/prestashop/prestashop/) and [mysql](https://hub.docker.com/_/mysql/) image combined for a [sloppy.io](https://sloppy.io) project. You can extend the json/yml with more variables from the official images.

## Start it

```
sloppy start -var=USERNAME:username -var=URI:mydomain.sloppy.zone -var=DBUSER:db-user-for-prestashop -var=DBPASS:db-prestashop-for-prestashop -var=DBROOT:db-root-password prestashop.yml

Example:

sloppy start -var=URI:prestashop.sloppy.zone -var=DBUSER:psadmin -var=DBPASS:secret -var=DBROOT:moresecret -var=ADMINMAIL:admin@mysite.de -var=ADMINPASSWD:mypasswd prestashop.yml 
```