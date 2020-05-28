# Prometheus_Grafana
Grafana App for Kubernetes
Kubernetes is an open-source system for automating deployment, scaling, and management of containerized applications.

The Grafana Kubernetes App allows you to monitor your Kubernetes cluster's performance. It includes 4 dashboards, Cluster, Node, Pod/Container and Deployment. It allows for the automatic deployment of the required Prometheus exporters and a default scrape config to use with your in cluster Prometheus deployment. The metrics collected are high-level cluster and node stats as well as lower level pod and container stats. Use the high-level metrics to alert on and the low-level metrics to troubleshoot.




Container Dashboard

Container Dashboard

Node Dashboard

Requirements
Currently only has support for Prometheus
For automatic deployment of the exporters, then Kubernetes 1.6 or higher is required.
Grafana 5.0.0+