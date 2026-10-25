<img src="assets/profile-v7.svg" alt="Ege Zambelli, Cloud and DevOps Engineer. My focus is the side that keeps products running: AWS and Azure, infrastructure as code, containers, CI/CD and production operations. Because I also build the frontend and backend, I design infrastructure with the whole product in mind. Focus: AWS, Azure, Terraform, Docker, Kubernetes, Helm, CI/CD. Backend: Python, FastAPI, Node.js, Go, PostgreSQL. Frontend: React, Next.js, TypeScript, React Native. Workflow: agentic AI coding with Claude Code; I review and test every change myself. Wrocław, PL. BEng Computer Science, WSB Merito, 2027. Contact: egezambelli1@gmail.com. Open source: Helmbulance, behavioural tests for Helm charts, in the Git Hospital organization." width="100%">

![AWS](https://img.shields.io/badge/AWS-000000?style=flat-square&logo=amazonwebservices&logoColor=ffffff)
![Azure](https://img.shields.io/badge/Azure-000000?style=flat-square&logo=microsoftazure&logoColor=0078D4)
![Terraform](https://img.shields.io/badge/Terraform-000000?style=flat-square&logo=terraform&logoColor=844FBA)
![Docker](https://img.shields.io/badge/Docker-000000?style=flat-square&logo=docker&logoColor=2496ED)
![Kubernetes](https://img.shields.io/badge/Kubernetes-000000?style=flat-square&logo=kubernetes&logoColor=326CE5)
![Python](https://img.shields.io/badge/Python-000000?style=flat-square&logo=python&logoColor=3776AB)
![FastAPI](https://img.shields.io/badge/FastAPI-000000?style=flat-square&logo=fastapi&logoColor=009688)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-000000?style=flat-square&logo=postgresql&logoColor=4169E1)
![Node.js](https://img.shields.io/badge/Node.js-000000?style=flat-square&logo=nodedotjs&logoColor=5FA04E)
![TypeScript](https://img.shields.io/badge/TypeScript-000000?style=flat-square&logo=typescript&logoColor=3178C6)
![React](https://img.shields.io/badge/React-000000?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=ffffff)
![React Native](https://img.shields.io/badge/React_Native-000000?style=flat-square&logo=react&logoColor=61DAFB)

#### What I work on

- **Cloud infrastructure** — production on AWS and Azure, infrastructure in Terraform, least-privilege IAM,
  secrets in SSM, backups and alarms
- **Containers and delivery** — Docker images, Helm charts, CI/CD pipelines with test gates and
  image scanning, automated deploys
- **The products on top** — SaaS platforms (real estate CRM, warehouse management), AI products,
  and iOS / Android apps with React Native

Most of it is private: products I own, build with partners, or deliver to clients.

#### Open source: Git Hospital

[**Git Hospital**](https://github.com/Git-Hospital) is an open-source organization I co-run: tools
that diagnose infrastructure and code, and show the evidence for every diagnosis.

**[Helmbulance](https://github.com/Git-Hospital/helmbulance)** is my main project there. It installs a
Helm chart on a throwaway kind cluster and runs the day-2 operations that static checks miss: upgrades
with and without the original values, reinstalls, Secret rotation, and upgrades under live traffic.
A finding is reported only when it reproduces on the cluster. I build the CLI and the test scenarios
(14 merged PRs).

Bugs it found in public charts went upstream as fixes:
[seaweedfs#11720](https://github.com/seaweedfs/seaweedfs/pull/11720) (merged),
[zero-to-jupyterhub-k8s#3997](https://github.com/jupyterhub/zero-to-jupyterhub-k8s/pull/3997) and
[semaphoreui/charts#35](https://github.com/semaphoreui/charts/pull/35) (in review).

#### Shipped

<table>
<tr>
<td width="50%" valign="top">
<a href="https://www.loomr.net"><img src="assets/loomr.jpg" alt="LOOMR website"></a>
<br><b><a href="https://www.loomr.net">LOOMR</a></b> — the platform site for a fashion design
studio: an interactive atelier with showroom, fabric library, design and stylist rooms.
</td>
<td width="50%" valign="top">
<a href="https://3.74.95.123.sslip.io"><img src="assets/plusemlak.jpg" alt="PlusEmlak real estate CRM"></a>
<br><b><a href="https://3.74.95.123.sslip.io">PlusEmlak</a></b> — CRM and automation for real
estate offices: listings, client CRM, AI matching and valuation, social media automation.
</td>
</tr>
</table>

#### Public repos

| Repo | |
| --- | --- |
| [prod-saas-aws](https://github.com/egezamb/prod-saas-aws) | Production SaaS on AWS in Terraform — ECS Fargate, RDS, ALB, observability, cost breakdown |
| [cloud-infrastructure](https://github.com/egezamb/cloud-infrastructure) | Case studies of production infrastructure I've built and run |
| [spacefit](https://github.com/egezamb/spacefit) | Virtual fitting room — React + Gemini vision |
| [ege-portfolio-2025](https://github.com/egezamb/ege-portfolio-2025) | Portfolio — Next.js, TypeScript, Tailwind, TR / PL / EN |
| [aws-terraform-starter](https://github.com/egezamb/aws-terraform-starter) | Secure-by-default Terraform starter for AWS |
| [TSP-sales-problem](https://github.com/egezamb/TSP-sales-problem) | Genetic algorithm for the travelling salesman problem, live visualisation |
