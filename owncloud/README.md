# ownCloud


## Start it

```
sloppy start -var=URI:mydomain.sloppy.zone -var=DBROOT:root-password-for-mysql -var=DBUSER:regular-mysql-user -var=DBPASS:regular-mysqluser-password owncloud.json

Example:

sloppy start -var=URI:ownklaut.sloppy.zone -var=DBROOT:myrootpwd -var=DBUSER:ownme -var=DBPASS:s3cure owncloud.json
```

During the setup process choose MySQL as Database and fill in username and password you defined for the mysql container. The hostname is mysql.backend.owncloud.YOUR-SLOPPY-USERNAME
