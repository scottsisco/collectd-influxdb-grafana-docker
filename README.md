# About


This repository shows how to use a docker compose file to setup a collectd, influxdb, grafana, nginx reverse proxy and letsencrypt stack,

You can use this repository to try collect system data, store it in influxdb and create graph chart in Grafana.


# How to

It's easy, just clone this repository and run:

```
$ docker-compose up -d
```

Then you can open:

- <http://hostname>  grafana web page (login with admin/admin)
