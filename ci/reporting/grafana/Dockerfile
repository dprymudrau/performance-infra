FROM grafana/grafana:7.5.7

COPY ./datasource.yaml /etc/grafana/provisioning/datasources
COPY ./dashboard.yaml /etc/grafana/provisioning/dashboards
COPY ./default.json /var/lib/grafana/dashboards
