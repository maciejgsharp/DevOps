# DevOps
WHR deployment Fargate cluster thru terraform:
Prerequisties:
1. Terraform is installed and in $PATH
2. AWS CLI is installed and configured to use IAM role/user.
Steps:
1. Please adjust variables in variables.tf:
  - app_image
  - app_port
  - fargate_cpu
  - fargate_memory
2. Execute: terraform init
3. Execute: terraform plan
4. Execute: terraform apply

Cleanup procedure:
Execute: terraform destroy
