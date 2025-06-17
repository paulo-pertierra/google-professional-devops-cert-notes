# Typical Cloud Monitoring Architecture

3 Layers:
1. Data collection layer - Collects metrics, logs, and traces from GKE, GCE, App Engine, etc.
2. Data storage layer - Cloud monitoring Storage and API, GCS, etc...
3. Data analysis and visualization layer - Cloud Monitoring Dashboards, Uptime Checks, Alert Policies, Notifications, Grafana, 3p notifications

## Platform Monitoring

Visibility of the GCP services, enabled by default. GCP Monitoring is recommended for platform monitoring, this is free. Over 1500 metrics.

Can still use 3p stuff tho.

Recommended Google Managed Prometheus (GMP) - part of Cloud Mon, GKE cluster and workload metrics available as prom format. Supports PromQL, natively integrated to Prom expression browser.

Ops Agent