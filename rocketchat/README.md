# Rocket.Chat

Open Source Slack Clone based on Meteor and MongoDB.

## Start it

```
$ sloppy start -var=URI:mydomain.sloppy.zone rocketchat.json
```

Example:
```   
$ sloppy start -var=URI:coolchat.sloppy.zone rocketchat.json
```

## Important remarks

Unfortunatly since Rocketchat uses [MongoDB replica sets](http://docs.mongodb.org/manual/replication/) and this example uses only 1 MongoDB server, you need to manually activate the replica set after the MongoDB container has started. 

The easiest way to do this is by running the following command in the MongoDB container using our console feature:
```
$ mongo admin --eval 'rs.initiate();'
```

For production, we would advise using multiple MongoDB servers. 