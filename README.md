# Vihari Reddy — Cloud & DevOps Portfolio

Source code for my personal portfolio site and its AWS static-site delivery workflow.

## About

I am a Cloud & DevOps engineer with 4+ years of enterprise operations experience at Cognizant. My hands-on work focuses on AWS infrastructure, Terraform, Ansible, Docker, Kubernetes, CI/CD, and observability.

## What this repository contains

- `website/` — responsive static portfolio site
- `.github/workflows/` — CI/CD workflow files, where configured
- `docs/` — architecture and deployment evidence

## Deployment model

The site is designed to be delivered as static content from Amazon S3, with GitHub Actions used to automate deployments. Cloud credentials are supplied through GitHub Actions secrets and are never committed to this repository.

## Featured work

- **PlatformForge** — Docker, Kubernetes, Helm, EKS, Prometheus/Grafana, Trivy
- **Roboshop platform** — Terraform, Ansible, AWS multi-tier networking, ALB/Auto Scaling
- **Infrastructure security alerting** — CloudTrail, EventBridge, SNS

## Local preview

```bash
cd website
python3 -m http.server 8080
```

Open http://localhost:8080.

## Security

- Do not commit AWS access keys, account IDs, private endpoints, or resume files containing sensitive personal data.
- Use GitHub Actions secrets or AWS IAM roles for deployment credentials.
- Review the repository before every public push.

## Status

The portfolio content is actively being updated to reflect verified projects and experience only.
