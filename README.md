# Merhaba, ben Ege 👋

```console
$ whoami
Cloud & DevOps engineer (junior) — Wrocław, Poland 🇵🇱
$ uptime
2+ years building AWS/Azure infra for paying clients · 3 products in production
$ cat /etc/motd
I don't just deploy infrastructure. I run it.
```

I'm a 3rd-year Software Development student at **WSB Merito Wrocław** (graduating Feb 2027), but my learning happens mostly outside the classroom: for the last two years I've been designing, deploying and **operating real infrastructure for paying clients** — Terraform-managed AWS stacks, CI/CD pipelines, TLS, backups, monitoring, and the 3 a.m. outages that come with them.

Right now I'm looking for a **junior Cloud / DevOps role** (Poland or remote EU) where I can do more of exactly that, with mentorship.

---

## 🔧 What I'm running in production

Private client repos — no links, but I'll gladly walk through architecture diagrams and war stories in an interview:

| System | What I own | Stack |
|---|---|---|
| **DEPOS** — warehouse stock SaaS, *live for a paying customer* | Full AWS estate as **Terraform** (~30 resources): EC2 + persistent EBS Postgres, Caddy auto-TLS, SSM secrets, daily `pg_dump`→S3 backups, custom domain, systemd-timer **CD pipeline**. Fixed real outages on a live system (ACME/TLS failure, ORM enum regression). | FastAPI · PostgreSQL 16 · React · Docker Compose · AWS |
| **EmlakPlus AI** — real-estate CRM/SaaS | The DevOps track: Terraform infra, **Helm** charts, Docker image pipeline, GitHub Actions CI | Terraform · Helm · K8s · GHA |
| **kirakasa** — deposit-escrow platform (pre-seed) | Co-founder; backend + DevOps in a 3-person team: monorepo CI gates (typecheck/lint/test/build), regulated-domain design — payment layer strictly mock until licensed | Next.js 15 · Prisma · pnpm · GHA |

## 📂 Public proof

| Repo | Why it matters |
|---|---|
| ☁️ [aws-terraform-starter](https://github.com/egezamb/aws-terraform-starter) | Production-ready Terraform baseline — VPC + EC2 + S3, secure defaults, CI |
| λ [aws-lambda-terraform-lab](https://github.com/egezamb/aws-lambda-terraform-lab) | Serverless lab as full IaC — scheduled EC2 stopper, Lambda via Function URL / HTTP / REST API |
| 🛠️ [sbatools](https://github.com/egezamb/sbatools) | Git Flow + trunk-based release automation, lint gates |
| 👕 [spacefit](https://github.com/egezamb/spacefit) | AI vision (Gemini) integrated into a production React app |
| ⚙️ [calculator-pytest-cicd](https://github.com/egezamb/calculator-pytest-cicd) | Minimal, clean pytest + GitHub Actions pipeline |
| 🚀 [ege-portfolio-2025](https://github.com/egezamb/ege-portfolio-2025) | Portfolio site — Next.js 14, TR/PL/EN i18n |

## 🧰 Toolbox

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0089D6?style=flat&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/K8s%20%2F%20Helm-326CE5?style=flat&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

## 🔐 Security corner

BSc thesis: **Red Team / Blue Team RAT detection** — built a C2 server (Flask + SocketIO), three evasion-tier clients, and a scapy-based statistical beacon detector; detection rates measured across evasion phases (**95% → 20% → 85%**). Defensive research under university supervision.

## 📫 Reach me

📧 **egezambelli@protonmail.com** · 📍 Wrocław, PL (Karta Pobytu — authorized to work) · 🌍 open to remote across Europe
