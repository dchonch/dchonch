---
description: "Dawit Nida — Senior Infrastructure & Platform Engineer"
---

# Dawit Nida

**Senior Infrastructure & Platform Engineer**
:material-github: [GitHub](https://github.com/dchonch) | :material-linkedin: [LinkedIn](https://www.linkedin.com/in/dawitnida/)

---

!!! info "Professional Summary"

    Senior Infrastructure and Platform Engineer with **8+ years of experience** operating high-scale production systems across **multi-cloud environments (GCP, AWS)**. Backed by a strong foundation in software engineering, I bring comprehensive expertise in Infrastructure as Code (Terraform), observability, database operations, and platform engineering. Proven track record of leading complex migrations (Redis, Elasticsearch, Datadog), automating developer platforms, and implementing API integrations across diverse data sources.

---

## Technical Skills

| Domain | Technologies |
|--------|-------------|
| **Cloud Platforms** | GCP (GKE, Cloud SQL, Cloud Run, Pub/Sub, WIF), AWS (EKS, EC2, RDS, ElastiCache, S3), Aiven (Managed Redis/MySQL/OpenSearch), Cloudflare (WAF, Workers, ZTNA) |
| **Kubernetes & Containers** | Helmfile, ArgoCD (GitOps), KEDA (Event-driven Autoscaling), Docker, GitHub ARC (Self-hosted Runners), GKE, EKS |
| **Infrastructure as Code** | Terraform (Multi-cloud, Module Library Design), Packer (VM Image Pipelines), Ansible (Provisioning & Automation), Digger (PR Automation) |
| **Observability** | Datadog (Multi-org/Region setup), Elastic Stack (Logstash, Elasticsearch, OpenSearch), Prometheus, Grafana, Redash |
| **Databases & Data** | Redis Enterprise (Cluster Ops), MySQL, PostgreSQL, ClickHouse, BigQuery DTS |
| **CI/CD & Security** | Renovate (Platform-wide Rollout), GitHub Actions, Jenkins, Aikido Security Scanning |
| **Languages** | Bash/Shell, Python, Terraform/HCL, PHP |

---

## Key Professional Projects

### Platform Engineering & Kubernetes

!!! success "GitHub ARC Rollout"

    Deployed GitHub Actions Runner Controller (ARC) on GKE and EKS, replacing legacy Jenkins CI with ephemeral, auto-scaling runners on Rocky Linux.

!!! success "Renovate Platform-Wide Deployment"

    Automated dependency management across the organization using self-hosted Renovate on Kubernetes, covering Helm, Terraform, Docker, Python, and PHP ecosystems.

!!! success "Temporal Workflow Engine"

    Orchestrated the deployment of Temporal on K8s across multiple regions, managing schema migrations and KEDA-based worker autoscaling.

!!! success "GKE Cluster Rebuild"

    Led the full migration of DevOps workloads (ArgoCD, observability stack) to a hardened GKE cluster, implementing ExternalSecrets API and updated networking policies.

### Infrastructure Migrations

!!! example "Redis Enterprise to Aiven"

    Migrated critical production workloads from self-hosted EC2 clusters to Aiven Managed Redis using RUMP with zero-downtime dual-write patterns.

!!! example "Elastic Stack Evolution"

    Architected a multi-year migration: Self-hosted K8s → AWS ES → Aiven OpenSearch → Elasticsearch with **Hot/Warm/Cold tiering** for cost-optimized log retention.

!!! example "Datadog US to EU Migration"

    Managed the compliance-driven migration of **355 dashboards and 2,000+ monitors**, ensuring observability continuity via dual-shipping during transition.

!!! example "Logstash EC2 to Kubernetes"

    Containerized Logstash pipelines with custom secret redaction for GCS, replacing manual server management with a GitOps-driven Helm workflow.

### Network & Security

!!! example "Cloudflare Modernization"

    Migrated DNS from Route 53 to Cloudflare; implemented WAF rules, ZTNA policies, and edge logic using **Cloudflare Workers** managed via Terraform.

---

## Operations & Technical Leadership

!!! note "Incident Response"

    Active member of on-call rotations since 2018; expert in production triage, postmortem authoring, and managing incident response for database and K8s failures.

!!! note "Team Enablement"

    Onboarded the majority of the current SRE/Platform team; authored core onboarding documentation and conducted architectural walkthroughs for new technologies (Temporal, KEDA).

!!! note "Legacy Decommissioning"

    Successfully phased out legacy Jenkins, EC2-based Logstash, and self-hosted Redis Enterprise clusters, significantly reducing operational overhead.
