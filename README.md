Execute Terraform Commands

# Initialize Terraform

terraform init

# Terraform Validate

terraform validate

# Terraform Plan to Verify what it is going to create / update / destroy

terraform plan

# Terraform Apply to Create EC2 Instance

terraform apply
Verify EC2 Instances and its Name
Step-03: Understand about count index
If we currently see all our EC2 Instances has the same name web
Lets name them by using count index web-0, web-1, web-2, web-3, web-4...

# Destroy Terraform Resources

terraform destroy

# Remove Terraform Files

rm -rf .terraform*
rm -rf terraform.tfstate*
