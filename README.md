<!-- Sai Kumar Valmiki | Cloud & DevOps Engineering Portfolio -->

<div align="center">

# Sai Kumar Valmiki

### Cloud & DevOps Engineer | AWS · Kubernetes · CI/CD

*Building reliable cloud infrastructure and automated delivery workflows.*

[![GitHub Projects](https://img.shields.io/badge/Projects-Explore%20my%20work-24292f?style=flat-square&logo=github)](https://github.com/valmiki-tech?tab=repositories)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/sai-kumar-82ba29265)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:valmikisaikumar1231@gmail.com)

</div>

---

## About

I'm a Computer Science Engineering graduate (B.Tech, 2024) focused on **AWS Cloud and DevOps engineering**, with approximately **1.5 years of professional experience**. I use hands-on projects to strengthen the practical skills behind repeatable infrastructure, automated delivery, containerized applications, and Kubernetes operations.

My approach is practical: version the configuration, automate repeatable work, scan what gets shipped, monitor application health, and document how another engineer can reproduce the result.

**Target roles:** AWS Cloud Engineer · DevOps Engineer  
**Growing toward:** Platform Engineering · SRE · DevSecOps

## Engineering focus

<div align="center">

| CLOUD & AUTOMATION | DELIVERY & PLATFORMS | OPERATE & IMPROVE |
|:---|:---|:---|
| AWS infrastructure, Terraform, Ansible | CI/CD, Docker, Kubernetes, GitOps | Monitoring, health checks, security scanning |
| Repeatable infrastructure changes | Traceable application releases | Troubleshooting and reliability practices |

</div>

## Technology stack

Skills are grouped by how they fit into my current work and learning. These labels describe my learning focus, not a claim of production-level proficiency in every tool.

<details open>
<summary><strong>01 — Hands-on tools and core concepts</strong></summary>

<p>
  <img src="https://skillicons.dev/icons?i=aws,linux,bash,git,github,docker,kubernetes,jenkins,ansible,terraform,python&perline=6" alt="AWS, Linux, Bash, Git, GitHub, Docker, Kubernetes, Jenkins, Ansible, Terraform and Python" />
</p>

- **AWS:** EC2, VPC, S3, IAM, Lambda, RDS, ALB/NLB, Auto Scaling, CloudWatch, EKS
- **Containers & orchestration:** Docker, Kubernetes, kubectl, eksctl
- **CI/CD & configuration:** Jenkins, GitHub Actions, Git, Ansible
- **Infrastructure as Code:** Terraform fundamentals, modules, workspaces, and state management
- **Systems & scripting:** Linux/Ubuntu, Bash, Python scripting, YAML, JSON, SQL, SSH

</details>

<details>
<summary><strong>02 — Currently building and practising</strong></summary>

- **GitOps:** Argo CD and declarative Kubernetes delivery
- **Packaging:** Helm charts and Kubernetes configuration patterns
- **Observability:** Prometheus, Grafana, Node Exporter, kube-state-metrics
- **Container security:** Trivy image scanning and safer delivery pipelines
- **Kubernetes operations:** health probes, resource requests/limits, troubleshooting, and local Kind labs

</details>

<details>
<summary><strong>03 — Planned exploration</strong></summary>

- **Infrastructure quality:** Checkov, policy checks, reusable Terraform modules
- **Observability:** OpenTelemetry for vendor-neutral telemetry
- **Platform engineering:** Backstage concepts, self-service workflows, reusable platform templates
- **Reliability:** SLIs/SLOs, alert quality, incident runbooks, and progressive delivery
- **Cloud security & FinOps:** least-privilege IAM, secrets management, tagging, budgets, and rightsizing
- **AI-assisted operations:** evidence-based log analysis and incident investigation with human review

</details>

---

## Featured engineering projects

<div align="center">

<a href="https://github.com/valmiki-tech/eks-gitops-project"><img src="https://github-readme-stats.vercel.app/api/pin/?username=valmiki-tech&repo=eks-gitops-project&theme=github_dark&hide_border=true" alt="Cloud-native GitOps project" /></a>
<a href="https://github.com/valmiki-tech/CICD-pipeline-using-Jenkins"><img src="https://github-readme-stats.vercel.app/api/pin/?username=valmiki-tech&repo=CICD-pipeline-using-Jenkins&theme=github_dark&hide_border=true" alt="Jenkins CI/CD project" /></a>
<a href="https://github.com/valmiki-tech/Application-Launched-usind-EKS"><img src="https://github-readme-stats.vercel.app/api/pin/?username=valmiki-tech&repo=Application-Launched-usind-EKS&theme=github_dark&hide_border=true" alt="AWS EKS application project" /></a>
<a href="https://github.com/valmiki-tech/Effortless-Website-Hosting-With-AWS"><img src="https://github-readme-stats.vercel.app/api/pin/?username=valmiki-tech&repo=Effortless-Website-Hosting-With-AWS&theme=github_dark&hide_border=true" alt="AWS website hosting project" /></a>

</div>

### 01 · Cloud-Native GitOps & Microservices Automation

[**Repository → eks-gitops-project**](https://github.com/valmiki-tech/eks-gitops-project)  
**Python · Docker · GitHub Actions · Trivy · GHCR · Kubernetes · Kind · Argo CD**

**Problem:** make application delivery more repeatable and ensure a change can be tested, scanned, versioned, and reflected in Kubernetes configuration.

**Implementation verified in the repository:**
- GitHub Actions validates Python syntax and runs unit tests.
- Docker builds a container image; Trivy scans for HIGH and CRITICAL vulnerabilities.
- The workflow publishes images to GitHub Container Registry with latest and commit-SHA tags.
- A successful publish updates the Kubernetes deployment manifest to the commit-specific image.
- Argo CD monitors the Git repository and synchronizes desired configuration to a local Kind cluster.
- Kubernetes resources include readiness/liveness probes and resource requests/limits.

**Demonstrates:** CI/CD workflow design, container security checks, image traceability, declarative delivery, and basic Kubernetes operations.

**Next improvements:** add Terraform-managed AWS infrastructure, Helm packaging, Prometheus/Grafana dashboards, and deployment/rollback runbooks.

<sub>Scope note: the repository documents a local Kind implementation. AWS EKS and Terraform are future enhancements for this project, not current implementation claims.</sub>

### 02 · Automated Website CI/CD Pipeline

[**Repository → CICD-pipeline-using-Jenkins**](https://github.com/valmiki-tech/CICD-pipeline-using-Jenkins)  
**GitHub · Jenkins · Ansible · Docker · AWS EC2**

**Problem:** reduce manual steps between a code change and deploying a website.

**Documented workflow:** GitHub stores the source; Jenkins runs the pipeline and builds a Docker image; Ansible configures remote hosts and deploys the container; AWS EC2 provides the hosting environment.

**Demonstrates:** pipeline orchestration, configuration management, container packaging, and cloud-hosted deployment concepts.

**Next improvements:** remove duplicated README content, document the actual Jenkinsfile and playbooks, add reproducible setup instructions, include test evidence, and document secrets/IAM and rollback practices.

### 03 · Application Deployment on Amazon EKS

[**Repository → Application-Launched-usind-EKS**](https://github.com/valmiki-tech/Application-Launched-usind-EKS)  
**Amazon EKS · Kubernetes · kubectl · eksctl · AWS CLI · Helm**

**Goal:** document the workflow for preparing AWS access and networking, creating an EKS cluster, and deploying workloads on Kubernetes.

**Repository contents include:** EKS prerequisites, AWS CLI/kubectl configuration, cluster setup commands, OIDC provider guidance, Fargate cluster creation, and AWS Load Balancer Controller setup instructions.

**Demonstrates:** familiarity with EKS deployment concepts and the tooling used to operate a managed Kubernetes cluster.

**Next improvements:** turn the long guide into a tested step-by-step tutorial; correct any outdated commands/policies; add architecture diagrams, prerequisites, cleanup/cost warnings, and evidence of a successful deployment. Verify commands against current AWS documentation before use.

### 04 · Multi-Site Website Hosting on AWS

[**Repository → Effortless-Website-Hosting-With-AWS**](https://github.com/valmiki-tech/Effortless-Website-Hosting-With-AWS)  
**Amazon VPC · Subnets · Route Tables · Internet Gateway · EC2 · SSH**

**Goal:** document the core steps for hosting a website on AWS.

**Documented topics:** VPC and subnet concepts, internet gateway and routing, EC2 instance setup, security group ports, SSH access, and website deployment using a template.

**Demonstrates:** foundational AWS networking and compute concepts.

**Next improvements:** clearly separate implemented resources from general instructions; add a clean architecture diagram, least-privilege network rules, deployment verification, teardown steps, and a Terraform version of the environment.

---

## Engineering roadmap

These are planned learning projects—not claims of completed implementations.

| Priority | Project | What it should demonstrate |
|:---:|---|---|
| 1 | **AWS infrastructure with Terraform** | VPC, public/private subnets, security groups, reusable modules, remote state, validation, and safe teardown |
| 2 | **Secure CI/CD pipeline** | Tests, image build, Trivy scanning, artifact versioning, least-privilege workflow permissions |
| 3 | **Kubernetes GitOps delivery** | Helm, Argo CD, environment configuration, sync health, rollback documentation |
| 4 | **Kubernetes observability** | Prometheus/Grafana dashboards, useful alerts, service health, and an incident runbook |
| 5 | **Progressive delivery lab** | Canary/blue-green concepts, release verification, and a documented rollback |
| 6 | **Platform engineering starter** | Reusable templates or a simple self-service workflow for creating a service |
| 7 | **AI-assisted troubleshooting lab** | Summarize logs and metrics with evidence, redact sensitive data, and require human approval before changes |

## GitHub activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=valmiki-tech&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github" alt="GitHub repository and contribution statistics" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=valmiki-tech&layout=compact&theme=github_dark&hide_border=true" alt="Most-used languages across public repositories" />

<img src="https://streak-stats.demolab.com?user=valmiki-tech&theme=github-dark-blue&hide_border=true" alt="GitHub contribution streak" />

</div>

<sub>Statistics are provided by external services and may be temporarily unavailable. The repository links above remain the primary source of project details.</sub>

## Training

- **AWS Cloud Computing & DevOps** — Seven Mentors training
- **Linux Administration** — RHCSA/RHCE training
- **Networking & Security** — CCNA training

<sub>Listed as training; formal vendor certification status is not asserted here.</sub>

## Connect

<div align="center">

**Interested in Cloud, DevOps, Kubernetes, GitOps, or infrastructure automation? Let's connect.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sai%20Kumar%20Valmiki-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/sai-kumar-82ba29265)
[![Email](https://img.shields.io/badge/Email-Start%20a%20conversation-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:valmikisaikumar1231@gmail.com)
[![Repositories](https://img.shields.io/badge/GitHub-Explore%20projects-161B22?style=for-the-badge&logo=github)](https://github.com/valmiki-tech?tab=repositories)

<br/>

**Automate with intent. Observe with purpose. Improve continuously.**

</div>
