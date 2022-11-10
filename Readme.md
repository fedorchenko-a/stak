Helm chart, consists of: kube-prometheus, kube-state-metrics, prometheus-node-exporter, grafana and prometheus-blackbox-exporter.
Installation
helm install [release_name] ./kube-prometheus-stack
Grafana include by default dashboard Blackbox Exporter (HTTP prober)
