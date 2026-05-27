<div align="center">

# Vila Brunette
### Platform Engineer · AWS · Kubernetes · Infrastructure Security

*Building the infrastructure that lets engineering teams move fast without breaking things.*

[![AWS SAA](https://img.shields.io/badge/AWS-Solutions_Architect_Associate-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://aws.amazon.com/certification/)
[![Terraform Associate](https://img.shields.io/badge/HashiCorp-Terraform_Associate-7B42BC?style=flat-square&logo=terraform&logoColor=white)](https://developer.hashicorp.com/certifications)
[![CKA](https://img.shields.io/badge/CNCF-CKA-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://www.cncf.io/certification/cka/)
[![CKS](https://img.shields.io/badge/CNCF-CKS-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://www.cncf.io/certification/cks/)

</div>

---

## About

8 years in infrastructure and cloud engineering, most recently focused on platform engineering in financial services. I build and operate the shared infrastructure layer — EKS clusters, GitOps workflows, CI/CD pipelines, and the security controls that sit across all of it.

I care about platforms that are self-service by design: engineering teams should be able to deploy confidently without needing to know what's underneath. I also care about security being enforced at the platform layer, not bolted on as an afterthought.

Open to **Platform Engineer**, **SRE**, and **Cloud Infrastructure** roles — FTE or contract, remote.

---

## Featured Work

### 🏗️ [aws-eks-platform](https://github.com/vbrunette/aws-eks-platform)
> Production-grade EKS infrastructure with Terraform

Multi-environment (dev/staging/prod) AWS EKS platform built with reusable Terraform modules. Private endpoints, KMS secrets encryption, IMDSv2 enforcement, IRSA for least-privilege pod access, and a full GitHub Actions CI/CD pipeline with plan-on-PR.

`Terraform` `AWS EKS` `KMS` `IAM/IRSA` `GitHub Actions` `VPC` `S3 Remote State`

---

### 🔄 [gitops-eks-platform](https://github.com/vbrunette/gitops-eks-platform)
> GitOps workload management with ArgoCD ApplicationSets

ApplicationSet-driven GitOps repo managing microservice deployments across three environments. Matrix generator auto-discovers services from directory structure — adding a new service requires zero ArgoCD changes. Includes Kustomize overlays, image promotion workflow, and manifest diff preview on PRs.

`ArgoCD` `ApplicationSet` `Kustomize` `Kubernetes` `GitOps` `GitHub Actions` `Helm`

---

### 🔒 [k8s-security-platform](https://github.com/vbrunette/k8s-security-platform)
> OPA Gatekeeper admission control + Falco runtime detection

Full Kubernetes security layer implementing CIS Benchmark controls via OPA Gatekeeper (deny privileged containers, block host namespaces, enforce resource limits, require secure securityContext) and MITRE ATT&CK-mapped Falco rules for runtime anomaly detection. Includes operational runbooks for both tools.

`OPA Gatekeeper` `Rego` `Falco` `eBPF` `CIS Benchmark` `MITRE ATT&CK` `CKS`

---

## Stack

| Layer | Tools |
|-------|-------|
| **Cloud** | AWS (EKS, VPC, IAM, KMS, ECR, S3, CloudWatch) |
| **Infrastructure as Code** | Terraform, Terragrunt |
| **Containers & Orchestration** | Kubernetes, Helm, Kustomize |
| **GitOps & CI/CD** | ArgoCD, GitHub Actions, Atlantis |
| **Security** | OPA/Gatekeeper, Falco, tfsec, Trivy |
| **Observability** | Prometheus, Grafana, CloudWatch, Datadog |
| **Languages** | HCL, Bash, Python, YAML |

---

## Certifications

| Certification | Issuer | Status |
|--------------|--------|--------|
| AWS Solutions Architect Associate | Amazon Web Services | ✅ Active |
| HashiCorp Terraform Associate | HashiCorp | ✅ Active |
| Certified Kubernetes Administrator (CKA) | CNCF | ✅ Active |
| Certified Kubernetes Security Specialist (CKS) | CNCF | ✅ Active |

---

<div align="center">

**Open to remote Platform Engineer / SRE / Cloud Infrastructure roles**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vila_Brunette-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINKEDIN_HANDLE)
[![Email](https://img.shields.io/badge/Email-vilabrunette%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:vilabrunette@gmail.com)

</div>
