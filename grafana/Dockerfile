ARG GRAFANA_VERSION

FROM grafana/grafana:${GRAFANA_VERSION}

ENV GF_PATHS_PROVISIONING=/etc/grafana/provisioning/

COPY ./provisioning /etc/grafana/provisioning/
COPY ./dashboards /etc/grafana/dashboards/
