# Requirements
- Terraform >= `0.11.1`
- `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` environment variables exported.

Commands to be used..
Go to the appropriate directory path

Initializing Terrraform remote backend:
terraform init -backend-config=terraform.remote

Run the terraform plan command
Terraform plan

Run the terraform apply command
terraform apply

After the process is completed successfully, connect to http://EC2_INSTANCE_IP/app1 and http://EC2_INSTANCE_IP/app2 in your browse
