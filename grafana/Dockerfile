FROM grafana/grafana:6.3.0-beta2

ARG LANG=en

COPY dashboards/${LANG}_* /var/lib/grafana/dashboards/
COPY provisioning/ /etc/grafana/provisioning/
