# Session 13: Kubernetes Storage, HPA & Probes

This session covers three pillars of production-grade cloud-native infrastructure: State Persistence, Elastic Auto-Scaling, and Application Health Diagnostics.

---

## Key Topics & Modules

1. **Kubernetes Storage & Persistence:**
   - **Volumes & HostPath**: Temporary vs persistent pod volume lifecycles.
   - **PersistentVolumes (PV)**: Cluster-level storage resources provisioned statically or dynamically.
   - **PersistentVolumeClaims (PVC)**: User requests for storage bound to matching PVs.
   - **StorageClasses**: Dynamic volume provisioning on cloud providers and local clusters.
   - Related Directories: [`01-volumes/`](file:///home/akshanshsinha/DevOps/devops-heros/session-13-storage-hpa-probes/01-volumes), [`02-persistent-storage/`](file:///home/akshanshsinha/DevOps/devops-heros/session-13-storage-hpa-probes/02-persistent-storage), [`03-storageclass/`](file:///home/akshanshsinha/DevOps/devops-heros/session-13-storage-hpa-probes/03-storageclass)

2. **Horizontal Pod Autoscaler (HPA):**
   - Automatically scaling pod replicas up and down based on observed CPU and memory metrics.
   - Installing and configuring the Kubernetes Metrics Server.
   - Defining resource requests/limits and HPA targets (e.g. 50% target CPU utilization).
   - Related Directory: [`04-hpa/`](file:///home/akshanshsinha/DevOps/devops-heros/session-13-storage-hpa-probes/04-hpa)

3. **Application Health Probes:**
   - **Startup Probe**: Knowing when slow-booting applications have initialized before other probes begin.
   - **Readiness Probe**: Determining whether a pod should receive inbound network traffic via Services.
   - **Liveness Probe**: Detecting deadlocks and triggering automated container restarts.
   - Related Directory: [`05-probes/`](file:///home/akshanshsinha/DevOps/devops-heros/session-13-storage-hpa-probes/05-probes)

4. **Hands-on Capstone Mini-Project:**
   - Complete production deployment integrating PVC storage, HPA auto-scaling, and health checks.
   - See [mini-project/README.md](file:///home/akshanshsinha/DevOps/devops-heros/session-13-storage-hpa-probes/mini-project/README.md) for full project walkthrough and manifests.
