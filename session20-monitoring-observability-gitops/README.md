# Session 20: Monitoring, Observability & GitOps

This session covers enterprise observability architectures (Metrics, Logs, and Traces) using Prometheus and Grafana, alongside modern Continuous Delivery with GitOps and Argo CD.

---

## Key Modules & Topics

1. **Observability Foundations:**
   - **Monitoring vs Observability**: Knowing when systems fail vs understanding why they fail.
   - **The Three Pillars**:
     - **Metrics**: Numeric time-series data measuring rates, errors, and duration (RED method).
     - **Logs**: Timestamped event records for debugging specific requests.
     - **Traces**: Distributed context tracking requests across microservice boundaries.
   - Related Directories: [`01-monitoring-vs-observability/`](file:///home/akshanshsinha/DevOps/devops-heros/session20-monitoring-observability-gitops/01-monitoring-vs-observability), [`02-metrics-logs-traces/`](file:///home/akshanshsinha/DevOps/devops-heros/session20-monitoring-observability-gitops/02-metrics-logs-traces)

2. **Metrics & Visualization with Prometheus & Grafana:**
   - Deploying Prometheus with custom `prometheus.yml` scrape configurations.
   - Querying time-series data using PromQL.
   - Connecting Grafana to Prometheus data sources and building real-time dashboards.
   - Related Directories: [`03-prometheus/`](file:///home/akshanshsinha/DevOps/devops-heros/session20-monitoring-observability-gitops/03-prometheus), [`04-grafana/`](file:///home/akshanshsinha/DevOps/devops-heros/session20-monitoring-observability-gitops/04-grafana)

3. **GitOps & Continuous Delivery with Argo CD:**
   - **The GitOps Paradigm**: Declarative infrastructure where Git is the single source of truth.
   - **Argo CD**: Kubernetes-native GitOps controller continuously reconciling desired Git state with actual live cluster state.
   - Automated sync policies, self-healing, and drift detection.
   - Related Directories: [`05-introduction-to-gitops/`](file:///home/akshanshsinha/DevOps/devops-heros/session20-monitoring-observability-gitops/05-introduction-to-gitops), [`06-git-as-source-of-truth/`](file:///home/akshanshsinha/DevOps/devops-heros/session20-monitoring-observability-gitops/06-git-as-source-of-truth), [`07-argocd/`](file:///home/akshanshsinha/DevOps/devops-heros/session20-monitoring-observability-gitops/07-argocd)

4. **Hands-on Capstone Mini-Project:**
   - Deploying a complete cloud-native stack: Kubernetes + Git repository + Argo CD automatic reconciliation + Prometheus & Grafana monitoring.
   - See [08-mini-project/README.md](file:///home/akshanshsinha/DevOps/devops-heros/session20-monitoring-observability-gitops/08-mini-project/README.md) for complete manifests and step-by-step verification.
