# Terraform Docker IaC Task

## Objective
Use Terraform to provision and manage a Docker Nginx container.

## Tools Used
- Terraform
- Docker
- Nginx
- GitHub Codespaces

## Terraform Workflow
1. Created Docker resources using `main.tf`
2. Ran `terraform init`
3. Ran `terraform plan`
4. Ran `terraform apply`
5. Verified resources using `terraform state list`
6. Tested Nginx using `curl http://localhost:8080`
7. Ran `terraform destroy` to remove the infrastructure

## Resources Created
- Docker Nginx image
- Docker Nginx container

## Result
The Nginx container was successfully created, tested, tracked with Terraform state, and destroyed using Terraform.
