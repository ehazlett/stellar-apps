# Centralized Cluster Logging
This app deploys a [Grafana](https://grafana.com/grafana/), [Loki](https://grafana.com/logs/),
and [Promtail](https://grafana.com/docs/loki/latest/clients/promtail/) stack. Promtail is deployed
as a global service to every agent and uses the default log path of `/var/lib/stellar/containers/`
for its logging dir. If you change that on your agents you will need to update it.
