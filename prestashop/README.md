# PrestaShop

The official [PrestaShop](https://hub.docker.com/r/prestashop/prestashop/) and [mysql](https://hub.docker.com/_/mysql/) image combined for a [sloppy.io](https://sloppy.io) project. You can extend the json/yml with more variables from the official images.

## Start it

```
sloppy start -var=USERNAME:username -var=URI:mydomain.sloppy.zone -var=DBUSER:db-user-for-prestashop -var=DBPASS:db-prestashop-for-prestashop -var=DBROOT:db-root-password prestashop.json
```
For example:

```
sloppy start -var=URI:prestashop.sloppy.zone -var=DBUSER:psadmin -var=DBPASS:secret -var=DBROOT:moresecret -var=ADMINMAIL:admin@mysite.de -var=ADMINPASSWD:mypasswd prestashop.json
```

## Notes
* After the containers have been started the installation of Prestashop will commence. Please note that it can take up to 5 minutes to complete. During this process no content is served by the webserver.
* To access the administration interface of Prestashop located at yourshopurl.com/admin, Prestashop requires you to delete the installation folder. The easiest way to do this is trought the console of the frontend/apache container by running the following command: `rm -rf /var/www/html/install`.
