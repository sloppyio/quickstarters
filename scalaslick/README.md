# scalaSlick


## Start it

```
sloppy start -var=URI:mydomain.sloppy.zone -var=ROOTPW:root-password-for-mysql -var=MYSQLUSER:regular-mysql-user -var=MYSQLPASSWORD:regular-mysqluser-password scalaslick.json

Example:
   
sloppy start -var=URI:claydonkey-scala.sloppy.zone -var=ROOTPW:myrootpwd -var=MYSQLUSER:ownme -var=MYSQLPASSWORD:s3cure scalaslick.json
```

During the setup process choose MySQL as Database and fill in username and password you defined for the mysql container. The hostname is mysql.backend.scalaslick.YOUR-SLOPPY-USERNAME

Demos
play-slick 1.1.0
play-slick-evolutions 1.1.0
using mysql

Git repository
https://github.com/claydonkey/sloppy-slick
Docker Repository
https://hub.docker.com/r/claydonkey/sloppy-slick/

## For Repository

##compile
```
sbt compile
```
##stage
```
sbt docker:stage
```
##build (locally) 
```
docker build -t claydonkey/sloppy-slick:local .
```
##run (from hub.docker)
```
docker-compose up
```
##run (locally)
```
docker run --env SLICK_DB_IP_ADDRESS={YOURIP} SLICK_DB_PORT=3306 SLICK_DB_NAME={YOURDBNAME} SLICK_DB_USER={YOURDBUSER} --name sloppy_slick -dp 9000:9000 claydonkey/sloppy-slick:local
```
