# Docker-compose
# InfluxDB
# + Telegraf
# + Chronograf
# + Kapacitor

To setup your dev environment : 

```
docker-compose up
```

Then go to your local chronograf http://localhost:8888

In chronograf setup the influxdb and kapacitor connection strings with their full local ip

* http:// IP :8086 for influxdb
* http:// IP :9092 for kapacitor

============================


Then go to your local chronograf http://localhost:8888
```
Config. Chronograf:
InfluxDB Connection
```
Connection URL: http://influxdb:8086
Connection Name: Influx1
Username: 
Password:
Telegraf Database Name: telegraf
```
