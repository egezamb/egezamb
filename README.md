<h1 align="center">Ege Zambelli</h1>

<p align="center">
  <strong>Cloud & DevOps Engineer (junior)</strong> — I don't just deploy infrastructure, I run it in production.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Wroc%C5%82aw,%20Poland-4A90D9?style=flat&logo=googlemaps&logoColor=white" />
  <img src="https://img.shields.io/badge/Open%20to%20Work-Junior%20Cloud%20%2F%20DevOps-brightgreen?style=flat" />
  <img src="https://img.shields.io/badge/WSB%20Merito-Feb%202027-orange?style=flat" />
</p>

---

### 🔧 Production systems I built and operate

Real products with real users — private client repos, so no links, but happy to walk through any of them in an interview:

- **DEPOS — warehouse stock management SaaS** *(live in production for a paying customer)*
  Designed and operate the full AWS stack with **Terraform** (~30 resources): EC2 + persistent EBS for PostgreSQL, Caddy reverse proxy with automatic Let's Encrypt TLS, secrets in **SSM Parameter Store**, daily `pg_dump` → S3 backups with retention, custom domain, and a systemd-timer **continuous deployment** pipeline (poll → build → zero-manual-step rollout). Stack: FastAPI · PostgreSQL 16 · React · Docker Compose. Debugged and fixed real outages (ACME/TLS failures, ORM enum regressions) on a live system.

- **EmlakPlus AI — real-estate CRM/SaaS**
  Own the DevOps track: Terraform infrastructure, **Helm** charts, Docker image pipeline, GitHub Actions CI.

- **kirakasa — deposit-escrow platform (pre-seed demo)**
  Co-founder / backend + DevOps in a 3-person team: pnpm monorepo (Next.js 15 · Prisma · PostgreSQL), CI with typecheck/lint/test/build gates, regulated-domain constraint design (strictly mock payment layer — no real money movement without a license).

---

### 📂 Selected public repositories

| Repo | What it shows | Stack |
|------|---------------|-------|
| ☁️ [**aws-terraform-starter**](https://github.com/egezamb/aws-terraform-starter) | Production-ready Terraform starter — VPC + EC2 + S3, secure defaults, CI | Terraform · AWS · GitHub Actions |
| λ [**aws-lambda-terraform-lab**](https://github.com/egezamb/aws-lambda-terraform-lab) | Serverless lab as full IaC — scheduled EC2 stopper + Lambda behind Function URL / HTTP API / REST API | Terraform · Lambda · API Gateway · Python |
| 🛠️ [**sbatools**](https://github.com/egezamb/sbatools) | Git Flow + trunk-based workflows, date-versioned release automation, lint gates | Python · GitHub Actions · Black/Flake8 |
| ⚙️ [**calculator-pytest-cicd**](https://github.com/egezamb/calculator-pytest-cicd) | Clean pytest + CI/CD pipeline demo | Python · pytest · GitHub Actions |
| 👕 [**spacefit**](https://github.com/egezamb/spacefit) | Virtual fitting room — AI vision API integrated into a production React app | React · Google Gemini Vision |
| 🚀 [**ege-portfolio-2025**](https://github.com/egezamb/ege-portfolio-2025) | Personal portfolio, TR / PL / EN i18n | Next.js 14 · TypeScript · Tailwind |

---

### 🧰 Toolbox

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0089D6?style=flat&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes%20%2F%20Helm-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**CI/CD & Operations**

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy%20%2F%20nginx-1F88C0?style=flat&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

---

### 🔐 Security side

BSc thesis: **Red Team / Blue Team RAT detection study** — built a C2 server (Flask + SocketIO), three evasion-tier RAT clients, and a scapy-based statistical beacon detector; measured detection rates across evasion phases (95% → 20% → 85%). Defensive research under university supervision.

---

### 📫 Contact

- 📧 egezambelli@protonmail.com
- 🌍 Wrocław, Poland — authorized to work in Poland (Karta Pobytu); open to remote across Europe
- 🎓 BSc Software Development, WSB Merito Wrocław — graduating **February 2027**
- ~2 years freelance AWS/Azure infrastructure for paying clients
