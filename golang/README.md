# Go

golang hello world example with Julien Schmidts httprouter. <br />
More information about httprouter you can find here: https://github.com/julienschmidt/httprouter

## Build and push docker image

docker build -t mydockerid/go-helloworld .
docker push mydockerid/go-helloworld

or use

koboltmarky/go-helloworld:latest as image

## Routes

The app has the following routes to test:

```
/
/hello/:name
```

## Start it

```
sloppy start -var=domain:mydomain.sloppy.zone httprouter.yml

Example:

sloppy start -var=domain:europa.sloppy.zone httprouter.yml
```
