# Flow Director

Flow Director is a new generation messaging platform that combines any 
cloud- and on-premise messaging products, databases and REST services with 
the simplicity of flow-based programming.

## Enabling additional Protocols

You can enable the following additional protocols by setting their ports from -1 to the port number in the json file:

- AMQP: 5672
- JMS: 4001
- MQTT: 1883
- ROUTING: 4100

Flow Director has an embedded protocol multiplexer and you can access all protocols
through the single public port (443 for TLS) on the Internet.


## Start it

```
sloppy start -var=URI:mydomain.sloppy.zone flowdirector.json

Example:

sloppy start -var=URI:fd4711.sloppy.zone flowdirector.json
```
