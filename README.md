<img width="100%" src="https://res.cloudinary.com/dnqk2jlds/image/upload/f_auto,q_auto,w_1400/v1784892308/lms-assets/github-builder-banner.png" alt="Banner" />

# DevOps Engineer

I am a DevOps Engineer who treats infrastructure as a product: versioned, tested, and observable. Most of my day is spent shortening the distance between a merged pull request and a safe production release — writing Terraform modules that teams can consume without reading the AWS docs, tuning Kubernetes autoscaling so services survive traffic spikes without over-provisioning, and building GitHub Actions and Jenkins pipelines that fail loudly in CI instead of quietly at 2 a.m. I have run blue/green and canary rollouts for services handling millions of requests a day, migrated hand-built EC2 fleets into reproducible EKS clusters, and cut cloud bills by finding the gap between what a workload requested and what it actually used.

I believe the best operations work is the work nobody notices, and that reliability comes from boring, repeatable systems rather than heroics. Every change should be reversible, every incident should end in a blameless write-up with a concrete action item, and every alert should be actionable — a pager that cries wolf is worse than no pager at all. I default to automating anything I have done manually twice, writing the runbook before I hand a system over, and giving developers self-service tooling so they own their deployments instead of filing tickets. Security and cost are not afterthoughts I bolt on at the end; they belong in the same pipeline as the tests.

### 🛠️ Tech Stack & Skills

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-6366f1?style=for-the-badge&logo=kubernetes&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-6366f1?style=for-the-badge&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-6366f1?style=for-the-badge&logo=ansible&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-6366f1?style=for-the-badge&logo=aws&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-6366f1?style=for-the-badge&logo=github actions&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-6366f1?style=for-the-badge&logo=jenkins&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-6366f1?style=for-the-badge&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-6366f1?style=for-the-badge&logo=grafana&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-6366f1?style=for-the-badge&logo=linux&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-6366f1?style=for-the-badge&logo=bash&logoColor=white) ![NGINX](https://img.shields.io/badge/NGINX-6366f1?style=for-the-badge&logo=nginx&logoColor=white) 

### 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats-ten-kohl-77.vercel.app/api?username=alexrivera-ai&show_icons=true&theme=radial" alt="GitHub Stats" />
  <img src="https://github-readme-stats-ten-kohl-77.vercel.app/api/top-langs/?username=alexrivera-ai&layout=compact&theme=radial" alt="Top Languages" />
</p>

### 💡 Expertise
Infrastructure as Code — I design modular, reusable Terraform and Ansible codebases with remote state, policy checks, and plan-review gates so any environment can be rebuilt from scratch on demand.

Container Orchestration — I run production Kubernetes clusters end to end, covering Helm packaging, autoscaler tuning, network policies, resource quotas, and zero-downtime rollout strategies.

CI/CD and Release Engineering — I build pipelines in GitHub Actions, GitLab CI, and Jenkins with parallel test stages, artifact caching, automated security scanning, and progressive delivery with fast rollback.

Observability and Incident Response — I instrument systems with Prometheus, Grafana, and structured logging, define SLOs and error budgets, and turn noisy dashboards into a small set of alerts that map directly to runbooks.

### 🚀 Featured Projects
Terraform Landing Zone — Multi-account AWS landing zone built from reusable Terraform modules with Terragrunt, cutting new environment provisioning from three days of manual setup to a 25-minute pipeline run.

Pipeline Accelerator — Rebuilt a monorepo GitHub Actions pipeline with dependency-aware job graphs, Docker layer caching, and matrix parallelism, dropping average CI time from 34 minutes to 6.

Karpenter Cost Tuning — Migrated an EKS platform to Karpenter with Spot-first node pools and right-sized resource requests, reducing monthly compute spend by 41% with no change to p99 latency.

Progressive Delivery — Introduced Argo Rollouts canary deploys gated on Prometheus error-rate queries, auto-aborting 12 bad releases and lowering change failure rate from 18% to 3%.

Observability Stack — Deployed a Prometheus, Thanos, and Grafana stack with SLO-based alerting that cut alert volume by 78% while reducing mean time to detect from 14 minutes to under 2.

Supply Chain Hardening — Replaced env-file secrets with Vault dynamic credentials and added Trivy scanning plus cosign image signing to every build, eliminating all long-lived static keys across 60 services.

### 🌐 Connect With Me

[<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />](https://linkedin.com/in/alex-rivera-dev) [<img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />](https://x.com/alexrivera_tech) [<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />](mailto:alex.rivera@techcraft.io) [<img src="https://img.shields.io/badge/Website-4338CA?style=for-the-badge&logo=googlechrome&logoColor=white" />](https://alexrivera.dev) 
