<!-- Sai Kumar Valmiki | Cloud & DevOps Portfolio -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:0F172A,50:1D4ED8,100:06B6D4&amp;height=190&amp;section=header&amp;text=Cloud%20Engineering&amp;fontSize=38&amp;fontColor=FFFFFF&amp;fontAlignY=38&amp;animation=fadeIn" alt="Animated blue cloud and DevOps banner" width="100%" />

# Sai Kumar Valmiki

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=20&amp;pause=1100&amp;color=38BDF8&amp;center=true&amp;vCenter=true&amp;width=700&amp;lines=AWS+Cloud+Engineer;DevOps+%7C+CI%2FCD+%7C+Automation;Docker+%7C+Kubernetes+%7C+GitOps;Building+reliable+cloud-native+workflows" alt="Animated typing text: AWS Cloud Engineer, DevOps, CI/CD, automation, Kubernetes and GitOps" />

**Automate delivery. Engineer for reliability. Keep learning.**

[![Projects](https://img.shields.io/badge/GitHub-Projects-161B22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/valmiki-tech?tab=repositories)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sai-kumar-82ba29265)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:valmikisaikumar1231@gmail.com)

</div>

---

## About

I'm a **Computer Science Engineering graduate (B.Tech, 2024)** focused on AWS Cloud and DevOps engineering, with approximately **1.5 years of professional experience**. I build hands-on projects around cloud infrastructure, CI/CD, containers, Kubernetes, and GitOps.

I value practical engineering: automate repeatable work, keep changes in version control, scan artifacts before delivery, monitor service health, and document how to reproduce and troubleshoot a deployment.

- **Target roles:** AWS Cloud Engineer and DevOps Engineer
- **Location:** India · Open to suitable remote opportunities worldwide
- **Career growth:** Platform Engineering, SRE, Cloud Security, DevSecOps, and AI-assisted operations

## Engineering focus

| Cloud & Infrastructure | Delivery & Platforms | Operate & Improve |
|:---|:---|:---|
| AWS, Terraform, Ansible | GitHub Actions, Jenkins, Docker | Prometheus, Grafana, CloudWatch |
| Infrastructure as Code | Kubernetes, Helm, Argo CD | Health checks, security scanning |
| Networking and access control | CI/CD and GitOps workflows | Troubleshooting and reliability |

## Technology stack

The categories below distinguish tools I use or have practised from areas I am actively developing. A tool appearing here does not imply production-level experience with it.

<details open>
<summary><strong>01 · Hands-on experience and core tools</strong></summary>

<div align="center">

<img src="https://skillicons.dev/icons?i=aws,linux,bash,git,github,docker,kubernetes,jenkins,ansible,terraform,python&amp;perline=6" alt="AWS, Linux, Bash, Git, GitHub, Docker, Kubernetes, Jenkins, Ansible, Terraform and Python" />

<sub>Tool icons are intentionally static for readability; the animated headline above carries the motion.</sub>

</div>

- **AWS:** EC2, VPC, S3, IAM, Lambda, RDS, ALB/NLB, Auto Scaling, CloudWatch, EKS
- **Containers:** Docker, Kubernetes, kubectl, eksctl
- **CI/CD and source control:** Jenkins, GitHub Actions, Git, GitHub, GitLab
- **Infrastructure automation:** Terraform fundamentals, modules, workspaces, state management, Ansible
- **Systems and scripting:** Linux/Ubuntu, Bash, Python, YAML, JSON, SQL, SSH

</details>

<details>
<summary><strong>02 · Currently learning and building</strong></summary>

- **GitOps and packaging:** Argo CD, Helm, declarative Kubernetes deployments
- **Observability:** Prometheus, Grafana, Node Exporter, kube-state-metrics
- **Container and pipeline security:** Trivy, vulnerability scanning, safer CI/CD workflows
- **Kubernetes operations:** probes, resource requests/limits, troubleshooting, and local Kind labs
- **Cloud infrastructure:** reusable Terraform patterns and safer state management

</details>

<details>
<summary><strong>03 · Planned exploration</strong></summary>

- **Infrastructure quality:** Checkov and policy-as-code practices
- **Observability:** OpenTelemetry, Loki, and Tempo
- **Platform engineering:** Backstage concepts and reusable self-service templates
- **Reliability:** SLIs/SLOs, error budgets, incident runbooks, and progressive delivery
- **Cloud security and FinOps:** least-privilege IAM, secrets management, budgets, tagging, and rightsizing
- **AI-assisted operations:** evidence-based log analysis with human review before operational changes

</details>

---

## Featured engineering projects

### 01 · Cloud-Native GitOps & Microservices Automation

**[Explore the repository →](https://github.com/valmiki-tech/eks-gitops-project)**

**Python · Docker · GitHub Actions · Trivy · GHCR · Kubernetes · Kind · Argo CD**

A local Kubernetes delivery project focused on repeatable builds, automated checks, container scanning, image publishing, and GitOps-based deployment updates.

**Implementation documented in the repository**
- GitHub Actions runs Python syntax checks and unit tests.
- Docker builds an application image; Trivy scans for HIGH and CRITICAL vulnerabilities.
- Images are published to GitHub Container Registry with version tags including the commit SHA.
- The workflow updates the Kubernetes deployment manifest to use the commit-specific image.
- Argo CD reconciles the desired configuration with a local Kind cluster.
- Kubernetes resources include readiness/liveness probes and resource requests/limits.

**Demonstrates:** CI/CD workflow design, image traceability, container security checks, declarative delivery, and Kubernetes fundamentals.

**Next improvements:** add a reproducible architecture diagram, Helm packaging, monitoring dashboards, and deployment/rollback runbooks.

> **Scope:** the repository describes a local Kind implementation. AWS EKS and Terraform are future enhancements for this project, not claims of a current EKS deployment.

### 02 · Automated Website CI/CD Pipeline

**[Explore the repository →](https://github.com/valmiki-tech/CICD-pipeline-using-Jenkins)**

**GitHub · Jenkins · Ansible · Docker · AWS EC2**

A project documenting an automated website delivery workflow connecting source control, Jenkins pipeline orchestration, Docker packaging, Ansible configuration/deployment, and an EC2 hosting environment.

**Demonstrates:** CI/CD concepts, configuration management, container packaging, and cloud-hosted deployment.

**Next improvements:** document the actual Jenkinsfile and Ansible playbooks, add exact setup and verification steps, and explain credential handling, failure recovery, and rollback.

### 03 · Application Deployment on Amazon EKS

**[Explore the repository →](https://github.com/valmiki-tech/Application-Launched-usind-EKS)**

**Amazon EKS · Kubernetes · kubectl · eksctl · AWS CLI · Fargate**

A practical guide to the tools and steps involved in preparing AWS access, configuring Kubernetes tooling, creating an EKS cluster, and setting up application delivery components.

**Repository topics include:** prerequisites, AWS CLI and kubectl setup, cluster commands, OIDC provider guidance, Fargate, and AWS Load Balancer Controller instructions.

**Demonstrates:** familiarity with the EKS toolchain and managed Kubernetes deployment concepts.

**Next improvements:** validate commands against current AWS documentation, add an architecture diagram, distinguish tested steps from reference instructions, and include cost warnings and cleanup commands.

### 04 · Website Hosting and AWS Networking

**[Explore the repository →](https://github.com/valmiki-tech/Effortless-Website-Hosting-With-AWS)**

**VPC · Subnets · Route Tables · Internet Gateway · EC2 · SSH**

A step-by-step hosting guide covering core AWS networking and compute concepts, including VPC setup, routing, EC2 configuration, security groups, SSH access, and web-server deployment.

**Demonstrates:** foundational AWS networking and compute knowledge.

**Next improvements:** clarify which resources were deployed versus described, add a network architecture diagram, tighten security group guidance, and provide verification and teardown steps. A Terraform implementation would make the setup more reproducible.

---

## Engineering roadmap

These are **planned projects**, not completed implementations.

| Priority | Planned project | Evidence to publish |
|:---:|---|---|
| 1 | **Terraform AWS infrastructure** | VPC, public/private subnets, reusable modules, remote state, validation, and safe teardown |
| 2 | **Secure CI/CD pipeline** | Automated tests, image builds, Trivy scans, versioned artifacts, and least-privilege workflow permissions |
| 3 | **Helm + Argo CD delivery** | Environment configuration, sync health, deployment history, and a tested rollback |
| 4 | **Kubernetes observability** | Prometheus/Grafana dashboards, useful alerts, application health, and an incident runbook |
| 5 | **Progressive delivery lab** | Canary or blue/green rollout, release verification, and rollback evidence |
| 6 | **Secure self-service platform starter** | Reusable templates, policy checks, and documented developer workflows |
| 7 | **AI-assisted troubleshooting lab** | Evidence-backed log summaries, sensitive-data redaction, and human approval for operational changes |

## GitHub activity

My repositories are the primary source of truth for project implementation. Dynamic statistics and activity cards are intentionally omitted here to keep this page readable and avoid relying on third-party rendering services that may be unavailable.

**[Browse all repositories →](https://github.com/valmiki-tech?tab=repositories)**

## Training

- **AWS Cloud Computing & DevOps** — Seven Mentors training
- **Linux Administration** — RHCSA/RHCE training
- **Networking & Security** — CCNA training

*These are listed as training; formal vendor certification status is not asserted.*

## Connect

<div align="center">

**Open to conversations about AWS, DevOps, Kubernetes, GitOps, and infrastructure automation.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sai%20Kumar%20Valmiki-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sai-kumar-82ba29265)
[![Email](https://img.shields.io/badge/Email-Start%20a%20conversation-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:valmikisaikumar1231@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Explore%20projects-161B22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/valmiki-tech?tab=repositories)

<br/>

**Build deliberately. Automate responsibly. Improve continuously.**

</div>
