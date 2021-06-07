FROM grafana/grafana:7.5.7

COPY ./datasource.yaml /etc/grafana/provisioning/datasources/datasource.yaml
COPY ./dashboard.yaml /etc/grafana/provisioning/dashboards/dashboards.yaml
COPY ./default.json /var/lib/grafana/dashboards/default.json
