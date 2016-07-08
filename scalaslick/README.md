# scalaSlick


## Start it

```
sloppy start -var=URI:mydomain.sloppy.zone -var=ROOTPW:root-password-for-mysql -var=MYSQLUSER:regular-mysql-user -var=MYSQLPASSWORD:regular-mysqluser-password scalaslick.json

Example:
   
sloppy start -var=URI:claydonkey-scala.sloppy.zone -var=ROOTPW:myrootpwd -var=MYSQLUSER:ownme -var=MYSQLPASSWORD:s3cure scalaslick.json
```

During the setup process choose MySQL as Database and fill in username and password you defined for the mysql container. The hostname is mysql.backend.scalaslick.YOUR-SLOPPY-USERNAME