# MASTER LEARNING TRACKER
## Shilpa — DevOps to Leadership Journey
### Started: July 1, 2026

---

## HOW TO USE THIS FILE
- [ ] = not done yet
- [x] = completed
- Add date when you complete each item
- Update resume bullets section as you learn

---

## CERTIFICATES ROADMAP

### In Progress / Planned
- [ ] CKA — Certified Kubernetes Administrator (Target: September 2026)
- [ ] CKAD — Certified Kubernetes Application Developer (Target: November 2026)
- [ ] CKS — Certified Kubernetes Security Specialist (Target: January 2027)
- [ ] AWS Solutions Architect Associate (Target: December 2026)

### Already Completed ✅
- [x] PMP — Project Management Professional
- [x] ISC2 CC — Certified in Cybersecurity
- [x] AWS Cloud Practitioner

### Where to Study
- CKA/CKAD/CKS → KodeKloud (kodekloud.com) — best platform, browser labs
- AWS SAA → Stephane Maarek course on Udemy
- Practice exams → killer.sh (included with CKA registration)

---

## 30-DAY LEARNING PLAN

### WEEK 1 — GitHub Actions and CI/CD (Jul 1–7)

- [x] Day 1 — GitHub Actions architecture (Jul 1) ✅
  - Event → Workflow → Job → Step
  - Self-hosted runners and SLC-29
  - set -eu shell hardening
  - Built first running pipeline on GitHub

- [ ] Day 2 — Shell scripting mastery
  - set -e, set -u, set -o pipefail
  - trap handlers
  - Error propagation
  - Idempotent scripts

- [ ] Day 3 — Custom actions
  - Composite vs Docker vs JavaScript actions
  - How cs-devops custom actions work
  - Building your own action

- [ ] Day 4 — Supply chain security
  - SHA pinning vs tag pinning
  - SLSA framework
  - Sigstore and Cosign
  - Why deprecated actions are dangerous

- [ ] Day 5 — Renovate bot deep dive
  - Configuration file structure
  - Datasources and versioning
  - Package rules and grouping
  - Automerge strategies

- [ ] Day 6 — GitHub Actions OIDC and Workload Identity
  - What is OIDC
  - Secretless authentication to cloud
  - How to replace long-lived tokens

- [ ] Day 7 — Week 1 Review and Project
  - Build complete hardened reusable pipeline
  - Week 1 reflection

### WEEK 2 — Kubernetes Deep Dive (Jul 8–14)

- [ ] Day 8  — Kubernetes architecture
- [ ] Day 9  — Pods, deployments, services
- [ ] Day 10 — Networking: CNI, NetworkPolicy, Ingress
- [ ] Day 11 — Storage: PV, PVC, StatefulSets
- [ ] Day 12 — RBAC: users, roles, bindings
- [ ] Day 13 — Kubernetes upgrades and Gardener
- [ ] Day 14 — Week 2 Review and Project

### WEEK 3 — GitOps, Helm, FluxCD (Jul 15–21)

- [ ] Day 15 — Helm deep dive
- [ ] Day 16 — Helm in CI/CD and OCI registries
- [ ] Day 17 — FluxCD architecture
- [ ] Day 18 — FluxCD advanced patterns
- [ ] Day 19 — GitOps patterns and multi-cluster
- [ ] Day 20 — Gardener deep dive
- [ ] Day 21 — Week 3 Review and Project

### WEEK 4 — Security, Observability, Platform (Jul 22–30)

- [ ] Day 22 — Vault secrets management
- [ ] Day 23 — Istio service mesh
- [ ] Day 24 — Prometheus and Grafana
- [ ] Day 25 — OpenSearch and Dynatrace
- [ ] Day 26 — DevSecOps and SonarQube
- [ ] Day 27 — SAP BTP architecture
- [ ] Day 28 — Platform Engineering thinking
- [ ] Day 29 — AI on Kubernetes
- [ ] Day 30 — Final review, mock interview, resume update

---

## MICRO LEARNINGS — Daily Useful Facts

### GitHub Actions
- [ ] Understand GITHUB_TOKEN default permissions
- [ ] Understand difference between secrets and vars
- [ ] Know how to use concurrency groups to cancel old runs
- [ ] Know how to use if: conditions on steps and jobs
- [ ] Understand artifact retention periods
- [ ] Know how to debug with tmate (SSH into runner)
- [ ] Understand reusable workflows vs composite actions
- [ ] Know how to pass outputs between jobs
- [ ] Understand caching dependencies (actions/cache)
- [ ] Know how to trigger one workflow from another

### Shell Scripting
- [ ] set -e — exit on error
- [ ] set -u — unset variables are errors
- [ ] set -o pipefail — catch pipe failures
- [ ] set -x — debug mode (print each command)
- [ ] trap — cleanup on exit or error
- [ ] $? — exit code of last command
- [ ] 2>&1 — redirect stderr to stdout
- [ ] /dev/null — discard output
- [ ] Difference between [ ] and [[ ]] in bash
- [ ] How to write idempotent scripts

### Kubernetes
- [ ] How etcd stores cluster state
- [ ] What kubelet does on each node
- [ ] How kube-scheduler picks a node
- [ ] What happens when you run kubectl apply
- [ ] Difference between Deployment and StatefulSet
- [ ] How liveness vs readiness probes work
- [ ] What a PodDisruptionBudget does
- [ ] How HorizontalPodAutoscaler works
- [ ] What happens during a rolling update
- [ ] How resource requests vs limits work
- [ ] What OOMKilled means at kernel level
- [ ] How ConfigMaps and Secrets differ
- [ ] What a ServiceAccount is and why it matters
- [ ] How DNS works inside a cluster
- [ ] Difference between ClusterIP, NodePort, LoadBalancer

### Helm
- [ ] Chart.yaml structure and fields
- [ ] values.yaml and values override order
- [ ] How templates work ({{ .Values.x }})
- [ ] Helm hooks and their use cases
- [ ] Difference between helm install and helm upgrade
- [ ] What helm --atomic does
- [ ] OCI registry push and pull
- [ ] Chart dependencies and requirements
- [ ] How to test a Helm chart (helm test)
- [ ] Chart versioning strategy (appVersion vs version)

### FluxCD
- [ ] How Flux reconciliation loop works
- [ ] Source controller vs Helm controller
- [ ] What a HelmRelease CRD looks like
- [ ] How Flux detects drift and corrects it
- [ ] How to suspend and resume a Flux resource
- [ ] How Flux handles secrets (SOPS, Vault)
- [ ] How to promote between environments
- [ ] Flux notifications and alerts
- [ ] How imageautomation works
- [ ] Difference between Flux v1 and v2

### Security
- [ ] What supply chain attack means
- [ ] How SHA pinning protects actions
- [ ] What SLSA framework levels mean
- [ ] How Cosign signs container images
- [ ] What SBOM is and why it matters
- [ ] How Vault dynamic secrets work
- [ ] What mTLS means in Istio
- [ ] How NetworkPolicy restricts traffic
- [ ] What least privilege means in RBAC
- [ ] How secret scanning works in GitHub

### Observability
- [ ] Difference between metrics, logs, traces
- [ ] How Prometheus scraping works
- [ ] What a PromQL query looks like
- [ ] How Grafana dashboards connect to Prometheus
- [ ] What an SLO and SLA mean
- [ ] How alerting rules work in Prometheus
- [ ] What OpenSearch index patterns are
- [ ] How Dynatrace APM differs from Prometheus
- [ ] What distributed tracing is
- [ ] How to debug a slow request end to end

### SAP Specific
- [ ] What Gardener shoot clusters are
- [ ] How btp-operator manages BTP services in K8s
- [ ] What SAP AI Core does
- [ ] How Marjory agent platform works
- [ ] What SLC-29 compliance requires
- [ ] How CCO (Customer Checkout) is deployed
- [ ] How DCH (Digital Currency Hub) differs from CCO
- [ ] What Cumulus and Sirius do for compliance
- [ ] How CAM manages access control
- [ ] What NoOps vision means for CS-DevOps

---

## WEEKLY PROJECTS

- [ ] Week 1 Project — Hardened CI/CD pipeline with composite action
- [ ] Week 2 Project — Production-grade Kubernetes namespace design
- [ ] Week 3 Project — Full GitOps pipeline (commit → cluster)
- [ ] Week 4 Project — Observability stack with SLO definition

---

## RESUME BULLETS (update as you learn)

### Completed and on resume
- [x] Migrated 28 repositories (73 workflow files) from deprecated SAP/project-piper-action to piper/piper-action@v1
- [x] Hardened 6+ GitHub Actions with set -eu shell error handling
- [x] Centralized hardcoded infrastructure URLs across all custom actions
- [x] Configured Renovate bot for automated dependency management
- [x] Restricted HANA Cloud database access to cluster IP ranges
- [x] Resolved Grafana and OpenSearch dashboard access issues across corporate VPN
- [x] Validated Kubernetes 1.33 upgrade compatibility
- [x] Provisioned AI workload system (ai-problem-solver-main01)
- [x] Designed automated Helm chart version bumping for Langfuse

### To add as you complete days
- [ ] Day 2 bullet — shell scripting
- [ ] Day 3 bullet — custom actions
- [ ] Day 4 bullet — supply chain security
- [ ] Week 1 project bullet
- [ ] Week 2 project bullet
- [ ] Week 3 project bullet
- [ ] Week 4 project bullet

---

## INTERVIEW QUESTIONS BANK

### Answered and ready
- [x] What is the difference between a job and a step in GitHub Actions?
- [x] Why does your team use self-hosted runners?
- [x] What does set -eu do and why does it matter?
- [x] Tell me about a large-scale migration you handled
- [x] How did you improve CI/CD reliability?
- [x] How do you handle dependency management at scale?
- [x] Describe a security improvement you made

### To prepare (unlock as you learn each day)
- [ ] How does Kubernetes scheduling work?
- [ ] What happens when a pod gets OOMKilled?
- [ ] How does FluxCD detect and correct drift?
- [ ] Explain GitOps vs traditional CI/CD push model
- [ ] How does Vault dynamic secrets work?
- [ ] What is mTLS and why does Istio use it?
- [ ] How would you design a multi-cluster deployment strategy?
- [ ] What is an SLO and how do you define one?

---

## COURSES TO COMPLETE

### Free
- [ ] TechWorld with Nana — GitHub Actions Tutorial (YouTube) — Week 1
- [ ] TechWorld with Nana — Kubernetes Tutorial (YouTube) — Week 2
- [ ] Viktor Farcic — FluxCD Tutorial (YouTube) — Week 3

### KodeKloud (paid — recommended ~$20/month)
- [ ] Kubernetes for Absolute Beginners
- [ ] Certified Kubernetes Administrator (CKA)
- [ ] Helm for Beginners
- [ ] HashiCorp Vault

### SAP Learning (free)
- [ ] Discover SAP BTP (learning.sap.com)
- [ ] SAP AI Core Basics (learning.sap.com)

### Udemy (buy during sale — never pay full price)
- [ ] Stephane Maarek — AWS Solutions Architect Associate
- [ ] Mumshad Mannambeth — CKA with Practice Tests

---

## PROGRESS SCORE (update weekly)

| Area | Week 1 | Week 2 | Week 3 | Week 4 |
|------|--------|--------|--------|--------|
| GitHub Actions | 6/10 | | | |
| Kubernetes | 4/10 | | | |
| Helm | 3/10 | | | |
| FluxCD/GitOps | 3/10 | | | |
| Security | 4/10 | | | |
| Observability | 3/10 | | | |
| SAP BTP | 3/10 | | | |
| Shell Scripting | 5/10 | | | |
| Communication | 5/10 | | | |
| Leadership | 4/10 | | | |
