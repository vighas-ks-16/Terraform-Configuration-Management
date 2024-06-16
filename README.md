# Terraform-Infrastructure-as-Code
Automation of EC2 Instance Deployment using Terraform


I'm excited to unveil my inaugural Terraform project, where I've conquered the challenge of automating the deployment of an EC2 instance on AWS, all without the hassle of manual intervention. 💻⚙️

But this achievement is merely the tip of the iceberg. 

Let me guide you through the intricate journey of Terraform's lifecycles and unveil how they've orchestrated this groundbreaking project: 

I have initially created an EC2 Instance (Test Server) in the Availability Zone --> us-east-1a (N. Virginia) .

![image](https://github.com/vighas-ks-16/Terraform-Configuration-Management/assets/107311113/1ec800f5-7c47-43b9-ac52-f74ba849f0bc)


terraform init : Prepares Terraform to understand and work with the project files. Initializes a backend where the Terraform can store its state. 
Define the infrastructure in configuration files.

```
terraform init
```

![image](https://github.com/vighas-ks-16/Terraform-Configuration-Management/assets/107311113/1043b937-712c-43ae-9343-7f95f82bfd1f)

main.tf :

![image](https://github.com/vighas-ks-16/Terraform-Configuration-Management/assets/107311113/94104c50-d533-495b-91be-126d74f72f4a)





terraform plan : When configuring Terraform with cloud provider, we should authenticate the  cloud provider (AWS) with the current working CLI. 
Review the changes that Terraform will make to the infrastructure.

 ```
terraform plan
```

![image](https://github.com/vighas-ks-16/Terraform-Configuration-Management/assets/107311113/23b247dd-5674-4a70-b743-ff6caa030545)


terraform apply : Terraform is converting the Terraform configuration files into APIs that AWS will understand. 
Terraform provisions your infrastructure and updates the state file.

```
terraform apply
```

![image](https://github.com/vighas-ks-16/Terraform-Configuration-Management/assets/107311113/c6910cb0-8cb9-4e09-91a0-2000b081a33f)

![image](https://github.com/vighas-ks-16/Terraform-Configuration-Management/assets/107311113/61fbafe5-6023-4060-a9e2-182ad2711923)




At the end of the Terraform process, I automated the deployment of an EC2 Instance (Terraform Demo) in the Availability Zone --> us-west-2a (Oregon) .

![image](https://github.com/vighas-ks-16/Terraform-Configuration-Management/assets/107311113/c6dfae0c-e300-410a-b12a-be82e56ee8e6)



Through Terraform, we can track the organization without manually logging into the cloud service provider. 

Using the state file, the Terraform tracks the changes in the cloud environment.


### Terraform Life Cycle 

![image](https://github.com/vighas-ks-16/Terraform-Configuration-Management/assets/107311113/b20d8e5d-4bc8-4caa-9dd8-b6ac67448bfa)


### Ideal Terraform Setup

![image](https://github.com/vighas-ks-16/Terraform-Configuration-Management/assets/107311113/acdf3c04-84c0-4ff3-91b5-a01b4a452868)


