# Metric Scope
### Advantage of separate:
- clear separation of concerns
- easier to automate because init a project is straightforward
- users/devs are going to get good permission restriction
but
-  if app is larger than 1 project, you have limited viewing angle

### Advantage of combined:
- better anaylsis, more data
- single pane of glass to view everything
but
- permissions will be super broad.

Always create a dedicated project to host monitoring config data, and use metrics scope to set up monitoring. If a project is not needed anymore, all other projects are not impacted because we have an external project
# Extras:
## Typical Cloud Monitoring Architecture

3 Layers:
1. Data collection layer - Collects metrics, logs, and traces from GKE, GCE, App Engine, etc.
2. Data storage layer - Cloud monitoring Storage and API, GCS, etc...
3. Data analysis and visualization layer - Cloud Monitoring Dashboards, Uptime Checks, Alert Policies, Notifications, Grafana, 3p notifications

## Platform Monitoring

Visibility of the GCP services, enabled by default. GCP Monitoring is recommended for platform monitoring, this is free. Over 1500 metrics.

Can still use 3p stuff tho.

Recommended Google Managed Prometheus (GMP) - part of Cloud Mon, GKE cluster and workload metrics available as prom format. Supports PromQL, natively integrated to Prom expression browser.

## Ops Agent

Based on OTEL, can collect custom metrics and make available with Cloud Mon. Datadog/NewRelic can be used for integrations.

## Hybrid Monitoring and Logging
![[Pasted image 20250617204525.png]]

