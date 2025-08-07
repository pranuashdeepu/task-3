README.md


# Terraform + Docker: Nginx Container

## Objective

Provision a local Docker container using Terraform.

## Tools Used
- Terraform
- Docker
- Ubuntu (local machine)

## Files
- main.tf: Terraform configuration file
- terraform_logs.txt: Logs of execution
- README.md: Explanation of what was done

## How to Run

1. Ensure Docker and Terraform are installed
2. Run:

	terraform init
   	terraform plan
   	terraform apply --auto--approve
	terraform destroy --auto--approve
