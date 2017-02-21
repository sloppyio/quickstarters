# Python

Python hello world example with flask <br />
More information about flask you can find here: http://flask.pocoo.org/

## Build and push docker image

docker build -t mydockerid/python-helloworld . <br />
docker push mydockerid/python-helloworld

or use

koboltmarky/python-helloworld:latest as image

## Start it

```
sloppy start -var=domain:mydomain.sloppy.zone flask.yml

Example:

sloppy start -var=domain:europa.sloppy.zone flask.yml -
```
