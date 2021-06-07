FROM influxdb:1.8.6

WORKDIR /app
COPY influxdb.conf /etc/influxdb/influxdb.conf
ENTRYPOINT influxd -config /etc/influxdb/influxdb.conf

