FROM grafana/grafana:latest
USER root
RUN apk add --no-cache curl
USER grafana
RUN grafana-cli plugins install alexanderzobnin-zabbix-app
RUN grafana-cli plugins install grafana-clock-panel
RUN grafana-cli plugins install marcusolsson-treemap-panel
