# Terraform-Configuration-Management
Automation of EC2 Instance Deployment using Terraform


I'm excited to unveil my inaugural Terraform project, where I've conquered the challenge of automating the deployment of an EC2 instance on AWS, all without the hassle of manual intervention. 💻⚙️

But this achievement is merely the tip of the iceberg. 

Let me guide you through the intricate journey of Terraform's lifecycles and unveil how they've orchestrated this groundbreaking project: 

terraform init : Prepares Terraform to understand and work with the project files. Initializes a backend where the Terraform can store its state. Define the infrastructure in configuration files.

terraform plan : When configuring Terraform with cloud provider, we should authenticate the 
 cloud provider (AWS) with the current working CLI. Review the changes that Terraform will make to the infrastructure.

terraform apply : Terraform is converting the Terraform configuration files into APIs that AWS will understand. Terraform provisions your infrastructure and updates the state file

I have initially created an EC2 Instance in the Availability Zone --> us-east-1a (N. Virginia) .

At the end of the Terraform process, I automated the deployment of an EC2 Instance in the Availability Zone --> us-west-2a (Oregon) .


Through Terraform, we can track the organization without manually logging into the cloud service provider. Using the state file, the Terraform tracks the changes in the cloud environment.
