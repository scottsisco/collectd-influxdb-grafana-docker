# About


This repository shows how to use a docker compose file to put collectd, influxdb and grafana behind an nginx reverse proxy that is using letsencrypt to issue an ssl cert for grafana.

You can use this repository to try collect system data, store it in influxdb and create graph chart in Grafana.


# How to

It's easy, just clone this repository and run:

```
$ docker-compose up -d
```

Then you can open:

- <http://hostname>  grafana web page (login with admin/admin)


