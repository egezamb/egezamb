### Ege Zambelli

Cloud / DevOps engineer who ships products end to end. I write the infrastructure as code,
put CI in front of every change, and keep an eye on what it costs to run.

```ini
role       = Cloud / DevOps engineer · full-stack builder
focus      = AWS · Terraform · Docker · CI/CD · Linux
also       = Node.js · Python · Next.js / React · PostgreSQL
building   = SaaS and AI-powered web products, end to end
location   = Wrocław, PL  (authorized to work in Poland)
education  = BSc Software Development, WSB Merito — Feb 2027
open_to    = junior cloud / DevOps roles · on-site or remote (EU)
contact    = egezambelli1@gmail.com
```

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

#### Selected work

| Project | What it is | CI |
| --- | --- | --- |
| [**prod-saas-aws**](https://github.com/egezamb/prod-saas-aws) | Production SaaS on AWS in Terraform: ECS Fargate, RDS Postgres, ALB, ECR, SSM secrets, least-privilege IAM, CloudWatch alarms, autoscaling. OIDC deploys from GitHub Actions. [Cost breakdown](https://github.com/egezamb/prod-saas-aws/blob/main/docs/COST.md): ≈ $75–80/mo, and how to get it to ~$30. | [![CI](https://github.com/egezamb/prod-saas-aws/actions/workflows/ci.yml/badge.svg)](https://github.com/egezamb/prod-saas-aws/actions/workflows/ci.yml) |
| [**cloud-infrastructure**](https://github.com/egezamb/cloud-infrastructure) | Anonymized case studies of infrastructure I designed and run: an AWS production deployment, Kubernetes + Helm, CI/CD and secrets hardening. | — |
| [**aws-terraform-starter**](https://github.com/egezamb/aws-terraform-starter) | Readable, secure-by-default Terraform starter (VPC, EC2, S3) with a validation pipeline. | [![Terraform CI](https://github.com/egezamb/aws-terraform-starter/actions/workflows/terraform.yml/badge.svg)](https://github.com/egezamb/aws-terraform-starter/actions/workflows/terraform.yml) |
| [**aws-lambda-terraform-lab**](https://github.com/egezamb/aws-lambda-terraform-lab) | A university Lambda lab rebuilt as IaC: scheduled EC2 stopper, Lambda behind Function URL, HTTP API and REST API. | [![Terraform CI](https://github.com/egezamb/aws-lambda-terraform-lab/actions/workflows/terraform.yml/badge.svg)](https://github.com/egezamb/aws-lambda-terraform-lab/actions/workflows/terraform.yml) |

Also: [spacefit](https://github.com/egezamb/spacefit) (React + Gemini virtual fitting room) ·
[TSP-sales-problem](https://github.com/egezamb/TSP-sales-problem) (genetic algorithm, live plot) ·
[ege-portfolio-2025](https://github.com/egezamb/ege-portfolio-2025) (Next.js, TR/PL/EN)

#### How I work

- **Infrastructure as code first.** No click-ops; `terraform plan` is the review.
- **CI gates every change.** Format, validate, test, build — then deploy.
- **Cost is a design input.** Know what it costs per month before it ships, and what to cut.
- **Write it down.** Architecture and decision records live next to the code.

Most of my day-to-day work is in private repos for clients and products I'm building.
