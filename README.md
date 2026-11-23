<!-- HEADER (same simple banner style as your original README, plus real text so the name always shows) -->
<div align="center">
  <img src="https://vercel.app" alt="banner" />
  <h1>Malka Manuranga</h1>
  <h3>Junior Cloud &amp; DevOps Engineer</h3>
</div>

<!-- TYPING ANIMATION -->
<div align="center">
  <img src="https://demolab.com" alt="typing" />
</div>

<p align="center">
  <img src="https://shields.io" />
  <img src="https://shields.io" />
</p>

<p align="center">
  <a href="https://github.com"><img src="https://shields.io" /></a>
  <a href="https://linkedin.com"><img src="https://shields.io" /></a>
  <a href="mailto:bmmanuranga@gmail.com"><img src="https://shields.io" /></a>
  <a href="https://docker.com"><img src="https://shields.io" /></a>
  <a href="https://stackoverflow.com"><img src="https://shields.io" /></a>
</p>

---

## 👋 About me

I'm a **BSc (Hons) Software Engineering graduate** (NSBM Green University) who builds **DevOps and cloud projects in public**. I care about the boring-but-vital parts of delivery: automated checks, least-privilege security, reproducible infrastructure and clear documentation.

- 🔭 Building: GitOps, CI/CD and Infrastructure-as-Code platforms
- 🎓 Studying: **AWS Certified Solutions Architect – Associate** *(in progress)*
- 🧪 Honesty rule: every project below marks what is **verified**, **written** or **planned**
- 💼 Background: Full Stack Intern (React, PostgreSQL, MongoDB) and Industrial Trainee (Agile project coordination)
- 📫 Reach me: **bmmanuranga@gmail.com**

---

## 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev" /><br/>
  <img src="https://skillicons.dev" />
</p>

<details>
<summary><b>Full toolbox</b></summary>

| Area | Tools |
|---|---|
| **Containers** | Docker (multi-stage, non-root, healthchecks), Compose, Docker Hub, GHCR |
| **Orchestration & GitOps** | Kubernetes, kind, Kustomize, Helm, ArgoCD, Kyverno, kubeconform |
| **IaC** | Terraform (modules, envs, validation), Ansible, AWS (VPC, SG, S3) |
| **CI/CD** | GitHub Actions (matrix, caching, least-privilege), Jenkins, Dependabot |
| **Security** | Trivy, npm audit, SSH hardening, fail2ban, encrypted S3, read-only root FS |
| **Observability** | Prometheus, PromQL, Alertmanager, Grafana, promtool tests |
| **Languages** | Python, JavaScript/Node.js, HCL, Bash, PowerShell, YAML |

</details>

---

## 🚀 Featured projects

| Project | What it shows | Status |
|---|---|---|
| **[gitops-platform](https://github.com)** | Kustomize overlays (dev/staging/prod), ArgoCD apps, 9 Kyverno policies, kubeconform in CI | ![](https://shields.io) ![](https://shields.io) ![](https://shields.io) |
| **[shortlink-platform](https://github.com)** | Containerised API: tests, Trivy, GHCR publish, Helm chart, Jenkins approval gate | ![](https://shields.io) ![](https://shields.io) |
| **[platform-infra](https://github.com)** | Reusable Terraform modules (VPC, SG, encrypted S3) and Ansible hardening roles | ![](https://shields.io) ![](https://shields.io) |
| **[observability-stack](https://github.com)** | Prometheus, Alertmanager, Grafana with alerts as code and promtool unit tests | ![](https://shields.io) ![](https://shields.io) |
| **[cloudpulse-platform](https://github.com)** | Node.js metrics API, image-size comparison (single vs multi-stage), CI | ![](https://shields.io) ![](https://shields.io) |
| **[orders-platform](https://github.com)** | Docker, Compose, Jenkins, Kubernetes end to end | ![](https://shields.io) |
| **[status-api](https://github.com)** | FastAPI, pytest, ruff, CI matrix on Python 3.11/3.12 | ![](https://shields.io) |

<sub>🟢 verified = ran or passed CI &nbsp;·&nbsp; 🟠 written/in progress = code exists, not yet proven live &nbsp;·&nbsp; 🔵 planned</sub>

---

## 🔄 How I like to ship

```mermaid
flowchart LR
    A[Commit / PR] --> B[Lint + Tests]
    B --> C[Secret + Dependency Scan]
    C --> D[Build Image Once]
    D --> E[Trivy Scan]
    E --> F[Push to Registry]
    F --> G[Update Git Manifest]
    G --> H[ArgoCD Sync]
    H --> I[Staging → Approved Prod]
```

---

## 📊 GitHub stats

<p align="center">
  <img height="170" src="https://vercel.app" />
  <img height="170" src="https://vercel.app" />
</p>
<p align="center">
  <img src="https://demolab.com" />
</p>
<p align="center">
  <img src="https://vercel.app" width="95%" />
</p>

---

## 🎯 Currently working on

- ✅ Connecting repos into one flow: build → scan → publish → GitOps deploy
- 🔐 Adding image signing (cosign) and policy enforcement (Kyverno in a real cluster)
- ☁️ A safe, budget-capped `terraform apply` to AWS to turn "written" into "verified"
- 📚 AWS Solutions Architect – Associate study

<div align="center">
  <img src="https://demolab.com" alt="footer typing" />
</div>

<img src="https://vercel.app" width="100%" alt="footer" />
