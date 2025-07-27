# DevOps Project

This is a simple DevOps project that demonstrates:
- Infrastructure provisioning using Terraform.
- CI/CD pipeline using GitHub Actions.
- Deployment of a Node.js application to AWS.

## Directory Structure
- `app/`: Application code.
- `iac/`: Terraform configuration for infrastructure.
- `.github/workflows/`: CI/CD pipeline.

## Prerequisites
- AWS account and credentials configured.
- Terraform installed locally (if running manually).
- Docker installed locally (for testing).

## Usage
1. Clone the repository.
2. Update the Terraform configuration with your AWS details.
3. Push changes to the `main` branch to trigger the CI/CD pipeline.