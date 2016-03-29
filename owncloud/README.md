# ownCloud


## Start it

```
sloppy start -var=URI:mydomain.sloppy.zone -var=ROOTPW:root-password-for-mysql -var=MYSQLUSER:regular-mysql-user -var=MYSQLPASSWORD:regular-mysqluser-password owncloud.json

Example:
   
sloppy start -var=URI:ownklaut.sloppy.zone -var=ROOTPW:myrootpwd -var=MYSQLUSER:ownme -var=MYSQLPASSWORD:s3cure owncloud.json
```

During the setup process choose MySQL as Database and fill in username and password you defined for the mysql container. The hostname is mysql.backend.owncloud.YOUR-SLOPPY-USERNAME