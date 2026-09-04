# Security Policy

## Reporting a vulnerability

Do not open a public issue containing credentials, access keys, private endpoints, or personal data. Report the finding privately to the repository owner.

## Deployment rules

- Store cloud credentials only in GitHub Actions secrets or through OIDC.
- Never commit .env files, access keys, private certificates, or exported resumes.
- Review public assets and outbound links before each deployment.
