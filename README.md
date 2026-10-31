# Hi, I'm Caleb Tetteh 👋

**Cloud & security engineer.** Software Engineer at Verizon · M.S. Cloud Computing (UMGC, Dec 2026) · B.S. Computer Science (Georgia Tech)

At Verizon I build the AWS microservices behind the **Verizon Family app**: real-time messaging and
location notifications with a **99.99% delivery success rate**, and Lambda services answering in
**under 100 ms** for 2 million users. In this portfolio I design and build cloud systems on AWS and
Azure that are **secure by default, cheap to run, and proven with evidence**: measured recovery
times, load tests, attack simulations, and cost per request.

---

## In plain terms

Every project below solves a real business problem: staying online when a data center fails, keeping
patient and payroll data private, connecting two cloud providers safely, shipping software without
shipping vulnerabilities. Each repository opens with a **2-minute plain-language summary** for
hiring managers, followed by the technical depth engineers look for.

## Start here, by role

| If you're hiring a… | Look at these first |
|---|---|
| **Cloud Solutions Architect / Cloud Architect** | [Architecture casebook](https://github.com/Monkmode-tech/cloud-architecture-casebook) · [Multi-region DR](https://github.com/Monkmode-tech/aws-multi-region-dr) · [AWS ↔ Azure hybrid network](https://github.com/Monkmode-tech/aws-azure-hybrid-network) |
| **Cloud Engineer** | [Secure three-tier platform](https://github.com/Monkmode-tech/aws-secure-three-tier-platform) · [Event-driven timesheet & payroll](https://github.com/Monkmode-tech/serverless-event-driven-timesheet) · [Hybrid network](https://github.com/Monkmode-tech/aws-azure-hybrid-network) |
| **Cloud DevOps / Platform Engineer** | [EKS DevSecOps pipeline](https://github.com/Monkmode-tech/eks-devsecops-pipeline) · [Event-driven timesheet](https://github.com/Monkmode-tech/serverless-event-driven-timesheet) · [Multi-region DR](https://github.com/Monkmode-tech/aws-multi-region-dr) |
| **Cloud Security / Security Engineer** | [Security guardrails & detection](https://github.com/Monkmode-tech/aws-security-guardrails-detection) · [EKS DevSecOps pipeline](https://github.com/Monkmode-tech/eks-devsecops-pipeline) · [Secure three-tier platform](https://github.com/Monkmode-tech/aws-secure-three-tier-platform) |

## Projects

| Project | The business problem it solves | Highlights |
|---|---|---|
| [**aws-secure-three-tier-platform**](https://github.com/Monkmode-tech/aws-secure-three-tier-platform) | A public website that stays up under traffic spikes and attacks | ECS Fargate autoscaling on requests + CPU, WAF, private data tier, KMS, load test, $50 budget guardrail |
| [**aws-azure-hybrid-network**](https://github.com/Monkmode-tech/aws-azure-hybrid-network) | Two clouds talking privately and surviving a link failure | IPsec VPN, BGP over APIPA, no public IPs anywhere, 11-check validation incl. packet capture |
| [**aws-multi-region-dr**](https://github.com/Monkmode-tech/aws-multi-region-dr) | Staying online when an entire AWS region fails | Route 53 health-checked failover, DynamoDB global tables, cross-region backups with Vault Lock, game day that measures RTO/RPO |
| [**aws-security-guardrails-detection**](https://github.com/Monkmode-tech/aws-security-guardrails-detection) | Catching and auto-fixing risky changes before they become breaches | 14 CIS detections, GuardDuty, Security Hub, auto-remediation Lambdas, ABAC for health data, attack simulations |
| [**eks-devsecops-pipeline**](https://github.com/Monkmode-tech/eks-devsecops-pipeline) | Shipping containers fast without shipping vulnerabilities | Trivy gate, SBOM, cosign keyless signing, Kyverno admission policies, Argo CD GitOps, SHA-pinned actions |
| [**serverless-event-driven-timesheet**](https://github.com/Monkmode-tech/serverless-event-driven-timesheet) | Correct, confidential payroll that never double-counts | Cognito RBAC, transactional outbox via EventBridge Pipes, exactly-once consumers, Step Functions payroll, ≈ $3/month |
| [**cloud-architecture-casebook**](https://github.com/Monkmode-tech/cloud-architecture-casebook) | Making architecture decisions leadership can trust | 7 case studies; executable TCO, availability and security-ROI models; Well-Architected self-review |

## How I work

- **Evidence over claims.** Results tables come from scripts that measure them: failover time,
  data loss, time-to-remediate, payroll to the cent.
- **Security is the default.** Keyless CI (OIDC), customer-managed keys, least-privilege roles, and
  every scanner exception justified in writing.
- **Cost is a design input.** Every repository documents its monthly cost; serverless designs run for a few dollars a month.
- **Fix, don't suppress.** When my own pipeline's scanner found vulnerabilities, I upgraded the
  framework (Spring Boot 3.5 → 4.0) rather than adding an ignore rule.
- **Write it down.** Runbooks, architecture decision records and honest "what I'd do differently" sections.

## Tools I use

![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?logo=argo&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?logo=splunk&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)

**AWS:** VPC, Site-to-Site VPN, Route 53, ECS/Fargate, EKS, Lambda, API Gateway, Step Functions, EventBridge, SQS/SNS,
DynamoDB, RDS, S3, KMS, IAM/Identity Center, Cognito, CloudTrail, GuardDuty, Security Hub, Config, AWS Backup, CloudWatch, X-Ray
· **Azure:** VNet, VPN Gateway, NSG, Entra ID · **Security:** Trivy, checkov, tflint, gitleaks, CodeQL, cosign, Kyverno

## Certifications

Preparing, in this order: **AWS Solutions Architect – Associate** → **HashiCorp Terraform Associate** →
**AWS Security – Specialty**. Each project's README maps its work to the exam domains it exercises.

## Experience

**Software Engineer, Galileo team · Verizon** (June 2024 – present)
- Build and optimize the microservices that are opening the **Verizon Family app** to non-Verizon
  customers, a user base projected to grow from 2 million to 26 million by the end of 2026.
- Lead engineering of **real-time messaging and pet-tracking notifications** on AWS and PubNub:
  low latency, high throughput, **99.99% delivery success**.
- Architected a high-concurrency targeting service (**Node.js, AWS Lambda, MongoDB, CDN**) that
  serves personalized promotion tiles to 2 million users in **under 100 ms**.
- Built **Splunk dashboards and automated alerts** for real-time failure detection, and improve
  latency with asynchronous processing and caching.

**Cloud Engineer Intern · ATPCO** (Dec 2023 – Jun 2024): EC2 hosting, GitHub Actions CI/CD,
Flask + React analytics dashboards, and Pytest suites that cut post-deployment issues by over 90%.

**Software Engineer Intern · Strava** (Summer 2023): monolith-to-microservices migration;
automated employee on/offboarding from 10 minutes to under 20 seconds (Scala, GraphQL, Kubernetes,
Prometheus/Grafana).

**Software Engineer Intern · Honeywell Aerospace** (Fall 2022): containerized releases to Kubernetes,
and NestJS performance improved by over 50%.

## Education

- **M.S. Cloud Computing**, University of Maryland Global Campus (expected Dec 2026). The projects above grew out of this coursework.
- **B.S. Computer Science**, Georgia Institute of Technology (May 2024)

📫 tettehcaleb@gmail.com · [LinkedIn](https://linkedin.com/in/calebtetteh/)
