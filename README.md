# Config Server and config client example

config-server running on port 8888 and using file syastem based config
http://localhost:8888/config-client-default.properties


config-client using config provided by the config-server

http://localhost:8889/rest/message

To refresh the config:

Invoke POST on http://localhost:8889/actuator/refresh


curl -X POST http://localhost:8889/actuator/refresh
