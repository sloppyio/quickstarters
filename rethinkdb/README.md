[RethinkDB](https://www.rethinkdb.com)
======================================


What is RethinkDB?
------------------

* **Open-source** database for building realtime web applications
* **NoSQL** database that stores schemaless JSON documents
* **Distributed** database that is easy to scale
* **High availability** database with automatic failover and robust fault tolerance

RethinkDB is the first open-source scalable database built for realtime applications. It exposes a new database access model -- instead of polling for changes, the developer can tell the database to continuously push updated query results to applications in realtime. RethinkDB allows developers to build scalable realtime apps in a fraction of the time with less effort.

To learn more, check out [rethinkdb.com](https://rethinkdb.com).


# RethinkDB on sloppy.io

This repo contains 2 yml files:

## rethinkdb.yml

Spins up a single rethinkdb instance. You can check the admin ui and play around. Start it using our dashboard at https://admin.sloppy.io ([howto-video](https://vimeo.com/203276406)) or the sloppy.io CLI with:

`sloppy start --var=URI:yourfreedomain.sloppy.zone rethinkdb.yml`

where `URI` is the free sloppy.zone domain to reach the RethinkDB admin user interface.

##rethinkdb-poll.yml

Starts rethinkdb and a polling app where you can watch polls in realtime

`sloppy start --var=URI:yourfreedomainforthepollapp.sloppy.zone --var=URI2:yourfreedomainforrethinkdbui.sloppy.zone rethinkdb-poll.yml`

where `URI` is the free sloppy.zone domain to reach the polling app and `URI2` the domain to reach the RethinkDB admin user interface. 

You can find the source code of the polling app here https://github.com/MikeMichel/rethink-poll