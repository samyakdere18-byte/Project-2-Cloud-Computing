# College Mini-Project: Automated Deployment of a Serverless Student Task Management Application Using Terraform-Based Infrastructure as Code

This repository contains the complete college mini-project implementation located in the [`student-task-manager-iac/`](./student-task-manager-iac/) directory.

## Quick Navigation

- **Project Root Directory**: [`student-task-manager-iac/`](./student-task-manager-iac/)
- **Terraform Configuration**: [`student-task-manager-iac/terraform/`](./student-task-manager-iac/terraform/)
  - [`providers.tf`](./student-task-manager-iac/terraform/providers.tf)
  - [`main.tf`](./student-task-manager-iac/terraform/main.tf)
  - [`variables.tf`](./student-task-manager-iac/terraform/variables.tf)
  - [`outputs.tf`](./student-task-manager-iac/terraform/outputs.tf)
  - [`terraform.tfvars.example`](./student-task-manager-iac/terraform/terraform.tfvars.example)
- **Application Code**: [`student-task-manager-iac/application/`](./student-task-manager-iac/application/)
  - [`worker.js`](./student-task-manager-iac/application/worker.js) (Cloudflare Worker & REST API)
  - [`index.html`](./student-task-manager-iac/application/index.html) (Student Dashboard UI)
  - [`style.css`](./student-task-manager-iac/application/style.css) (Clean Light Theme with Navy Accents)
  - [`script.js`](./student-task-manager-iac/application/script.js) (Frontend API Client & State)
- **CI/CD Pipeline**: [`student-task-manager-iac/.github/workflows/deploy.yml`](./student-task-manager-iac/.github/workflows/deploy.yml)
- **Submission Screenshots Checklist**: [`student-task-manager-iac/screenshots/README.md`](./student-task-manager-iac/screenshots/README.md)
- **Comprehensive Project Documentation**: [`student-task-manager-iac/README.md`](./student-task-manager-iac/README.md)

## Quick Start (Local Testing)

```bash
cd student-task-manager-iac
npm test    # Run 20 automated unit tests (100% pass)
npm run dev # Run local emulation server on http://localhost:8787
```

Please refer to [`student-task-manager-iac/README.md`](./student-task-manager-iac/README.md) for full project documentation, architectural diagrams, Cloudflare setup, and viva preparation.
