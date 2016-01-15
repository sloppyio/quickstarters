# ownCloud


## Start it

```
sloppy start owncloud.json  -var=URI:mydomain.sloppy.zone,ROOTPW:root-password-for-mysql,MYSQLUSER:regular-mysql-user,MYSQLPASSWORD:regular-mysqluser-password
Example:
   
sloppy start owncloud.json  -var=URI:ownklaut.sloppy.zone,ROOTPW:myrootpwd,MYSQLUSER:ownme,MYSQLPASSWORD:s3cure
```

During the setup process choose MySQL as Database and fill in username and password you defined for the mysql container. The hostname is mysql.backend.owncloud.YOUR-SLOPPY-USERNAME