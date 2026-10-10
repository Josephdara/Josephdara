<h1 align="center">Joseph Olutimehin</h1>

<p align="center">
  <b>Cloud Engineer · Toronto, Canada</b><br/>
  Cloud infrastructure, built with a security mindset.
</p>

<p align="center">
  <a href="https://josephdara.com"><img src="https://img.shields.io/badge/Website-josephdara.com-111827?style=flat-square&logo=googlechrome&logoColor=white" alt="Website"/></a>
  <a href="https://linkedin.com/in/joseph-olutimehin"><img src="https://img.shields.io/badge/LinkedIn-joseph--olutimehin-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://josephdara.hashnode.dev"><img src="https://img.shields.io/badge/Blog-Hashnode-2962FF?style=flat-square&logo=hashnode&logoColor=white" alt="Hashnode"/></a>
  <a href="https://twitter.com/jhoe0x"><img src="https://img.shields.io/badge/X-@jhoe0x-000000?style=flat-square&logo=x&logoColor=white" alt="X"/></a>
  <a href="https://josephdara.com/Joseph_Olutimehin_Resume.pdf"><img src="https://img.shields.io/badge/Resume-PDF-EA4335?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="Resume"/></a>
</p>

---

I'm Joseph. I build and operate infrastructure on Google Cloud with Terraform, Kubernetes, and Cloud Build.

Before moving into cloud full-time, I spent four years in blockchain security and smart contract development, most recently as a Security Engineer at Coinbase, reviewing bridges, payment protocols, and network upgrades securing billions of dollars. That background shapes how I build: least-privilege IAM, private-by-default networking, and observability in place before the first incident.

<a href="https://www.credly.com/badges/9600f599-8fd9-478e-bba6-6ac2f97716d9"><img src="https://img.shields.io/badge/Google_Cloud_Certified-Associate_Cloud_Engineer-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Google Cloud Certified Associate Cloud Engineer"/></a>

**Open to** cloud, platform, and SRE roles in Toronto or remote. [Get in touch](mailto:jsatimehin@gmail.com).

## Featured projects

### [GKE Application Platform](https://github.com/Josephdara/gke-platform)

A private GKE platform that brings GitOps delivery, supply-chain checks, and workload security together, provisioned with Terraform.

- GitOps delivery with Argo CD and Helm, with rollback by Git revert
- Cloud Build pipelines with image scanning, SBOMs, and provenance
- Workload Identity, Secret Manager, and default-deny network policies
- Kyverno admission policies, Pod Security, and namespace RBAC
- Prometheus alerting, with load and disruption testing

[Source](https://github.com/Josephdara/gke-platform) · [Write-up](https://josephdara.hashnode.dev/gke-platform-1) · [Test evidence](https://github.com/Josephdara/gke-platform/blob/main/platform/evidence/README.md)

### [Stablecoin Whale Monitor](https://swm.josephdara.com/)

A live Google Cloud platform that tracks large USDC and USDT transfers on Ethereum. It started on Compute Engine VMs and evolved into a Terraform-managed serverless architecture.

- Cloud Run Worker Pool indexer that writes confirmed transfers as immutable objects to private Cloud Storage
- Cloud Run API serving from that store, with Pub/Sub-driven email alerts on large transfers
- Next.js dashboard behind a global external Application Load Balancer, Cloud CDN, and Cloud Armor
- Least-privilege CI/CD and monitoring across the platform

[Live](https://swm.josephdara.com/) · [Source](https://github.com/Josephdara/stablecoin-whale-monitor) · [Write-up](https://josephdara.hashnode.dev/gcp-swm-3-terraform)

### [Bank Shared VPC & PSC](https://github.com/Josephdara/bank-shared-vpc-psc)

A banking-style, four-project Google Cloud network with centralized governance and private service access, built entirely in Terraform.

- Shared VPC with subnet-level IAM delegation
- Identity-based firewall rules and an internal load balancer
- Private Service Connect access from a partner VPC
- VPC Flow Logs aggregated into BigQuery

[Source](https://github.com/Josephdara/bank-shared-vpc-psc) · [Write-up](https://josephdara.hashnode.dev/networking-psc)

## Toolkit

<p>
  <img src="https://skillicons.dev/icons?i=gcp,terraform,kubernetes,docker,linux,bash,prometheus,grafana,ts,nodejs,py,rust,solidity,nextjs,react,fastapi,redis&perline=20" alt="Toolkit"/>
</p>

| Area | Tools |
| --- | --- |
| Google Cloud | Compute Engine, Cloud Run, GKE, Cloud Storage, Cloud SQL, Pub/Sub, Artifact Registry, Cloud CDN, Cloud Armor, IAM, VPC |
| IaC & delivery | Terraform, Cloud Build, GitHub Actions, Docker, Helm, Kustomize, Argo CD |
| Networking | VPC design, Cloud NAT, load balancing, Gateway API, DNS, TLS |
| Security | Least-privilege IAM, Workload Identity, Kubernetes RBAC, network policies, Pod Security, Kyverno, threat modelling, secure SDLC |
| Observability | Cloud Monitoring, Cloud Logging, Prometheus, PromQL, uptime checks, SLO and alerting design |
| Languages | TypeScript, JavaScript (Node.js), Python, Rust, Solidity, Bash |

## Writing

- [Building a Secure Kubernetes Platform on GKE: Design Decisions, GitOps, and Failure Testing](https://josephdara.hashnode.dev/gke-platform-1)
- [Enterprise GCP Networking in Practice: Shared VPC for Governance, Private Service Connect for Isolation](https://josephdara.hashnode.dev/networking-psc)
- Stablecoin Whale Monitor series
  - [Part 1: Building and Deploying a Blockchain Indexer on Google Cloud](https://josephdara.hashnode.dev/gcp-swm-1-vm)
  - [Part 2: From Two VMs to Cloud Run](https://josephdara.hashnode.dev/gcp-swm-2-cloudrun-gke)
  - [Part 3: From Cloud Run Experiment to Terraform-Managed Platform](https://josephdara.hashnode.dev/gcp-swm-3-terraform)


<p align="center"><sub>B.Sc. Mathematics · <a href="https://josephdara.com">josephdara.com</a> · josephdara.eth</sub></p>
