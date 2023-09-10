sources: 
1. https://developer.hashicorp.com/terraform/tutorials/aws-get-started/aws-build
2. https://developer.hashicorp.com/terraform/tutorials/cloud-get-started/cloud-login


prerequisites:
* terraform cli
* aws cli

commands:
1. `terraform init` > initialize tf scm files
2. `terraform fmt` > format config files
3. `terraform validate` > validate config files
4. `terraform apply` > create infra
5. `terraform show` > inspects the current state
6. `terraform login` > login to tfc (terraform cloud)

IMPORTANT! store your state file securely and restrict access to only trusted team members who need to manage your infrastructure