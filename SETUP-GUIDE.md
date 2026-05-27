# GitHub Profile Setup Guide
## vbrunette (or your chosen username)

---

## Step 1 — Create the new account

1. Go to https://github.com/signup
2. Use **vilabrunette@gmail.com** or a dedicated professional email
3. Pick username: `vbrunette` (recommended) or your preferred handle
4. Verify email

---

## Step 2 — Create the Profile README repo

This is the special repo that appears on your profile page.

1. Click **New repository**
2. Set repo name to **exactly your username** (e.g. `vbrunette`)
3. Check **Public**
4. Check **Add a README file**
5. Click **Create repository**
6. Replace the default README.md content with the contents of `README.md` from this folder
7. Update the LinkedIn URL placeholder: replace `YOUR_LINKEDIN_HANDLE` with your actual LinkedIn profile handle

---

## Step 3 — Upload the three repos

For each of the three zips (`aws-eks-platform`, `gitops-eks-platform`, `k8s-security-platform`):

### Option A — GitHub web UI (easiest)
1. Create a new repo with the exact name (e.g. `aws-eks-platform`)
2. Set to **Public**, no README
3. On your computer, unzip the downloaded file
4. Open terminal in the unzipped folder and run:

```bash
git init
git add .
git commit -m "feat: initial platform infrastructure"
git branch -M main
git remote add origin https://github.com/vbrunette/aws-eks-platform.git
git push -u origin main
```

Repeat for the other two repos.

### Option B — GitHub CLI (faster if you have gh installed)
```bash
# Install gh: https://cli.github.com
gh auth login

# For each repo:
cd aws-eks-platform
git init && git add . && git commit -m "feat: initial platform infrastructure"
gh repo create vbrunette/aws-eks-platform --public --source=. --push

cd ../gitops-eks-platform
git init && git add . && git commit -m "feat: initial gitops platform"
gh repo create vbrunette/gitops-eks-platform --public --source=. --push

cd ../k8s-security-platform
git init && git add . && git commit -m "feat: initial security platform"
gh repo create vbrunette/k8s-security-platform --public --source=. --push
```

---

## Step 4 — Configure each repo on GitHub

For each repo, go to the repo page → click the ⚙️ gear icon next to "About":

### aws-eks-platform
- **Description:** `Production EKS platform — Terraform modules, private endpoints, IRSA, KMS encryption, GitHub Actions CI/CD`
- **Website:** *(leave blank)*
- **Topics:** `terraform` `aws` `eks` `kubernetes` `infrastructure-as-code` `platform-engineering` `github-actions` `devops`

### gitops-eks-platform
- **Description:** `GitOps platform — ArgoCD ApplicationSets, Kustomize overlays, multi-environment microservice deployment`
- **Website:** *(leave blank)*
- **Topics:** `argocd` `gitops` `kubernetes` `kustomize` `helm` `platform-engineering` `applicationset` `devops`

### k8s-security-platform
- **Description:** `Kubernetes security — OPA Gatekeeper admission control, Falco runtime detection, CIS Benchmark, MITRE ATT&CK`
- **Website:** *(leave blank)*
- **Topics:** `kubernetes` `security` `opa` `gatekeeper` `falco` `cis-benchmark` `devsecops` `cks`

---

## Step 5 — Pin the repos

1. Go to your profile page (github.com/vbrunette)
2. Click **Customize your pins**
3. Pin in this order:
   1. `aws-eks-platform`
   2. `gitops-eks-platform`
   3. `k8s-security-platform`

This order tells a story: infrastructure → workloads → security.

---

## Step 6 — Profile settings

Go to **Settings → Public profile**:

- **Name:** Vila Brunette
- **Bio:** `Platform Engineer · AWS · EKS · Terraform · GitOps · Open to remote roles`
- **Location:** New York, NY
- **Email:** vilabrunette@gmail.com *(optional — only shows if you enable it)*
- **LinkedIn:** your LinkedIn URL

---

## Step 7 — Update the Profile README LinkedIn link

In your `vbrunette/vbrunette` README.md, replace:
```
YOUR_LINKEDIN_HANDLE
```
With your actual LinkedIn profile URL slug (the part after linkedin.com/in/).

---

## What the profile will look like to a recruiter

1. Lands on github.com/vbrunette
2. Sees: name, bio, 4 cert badges, short professional summary, 3 pinned repos with descriptions
3. Clicks `aws-eks-platform` → sees architecture diagram, full README, 20+ Terraform files
4. Clicks `k8s-security-platform` → sees Rego policies, Falco rules, runbooks
5. Closes tab and sends you a message

Total time on profile before deciding you're worth reaching out to: ~2 minutes.
