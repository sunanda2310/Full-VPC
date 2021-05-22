# Full-VPC
This repository contains terraform code which when executed through Jenkinsfile, creates Virtual Private Cloud configuration, EC2 instances & other necessary configurations in the AWS cloud. 
This repository consist of following files:

**Jenkinsfile**: This file basically consist of the pipeline code & steps that will eventually run through jenkins CI/CD tool.

**full_vpc_code.tf**: This file consist of Terraform code that will run via Jenkins and will create Cloud resources on AWS Public cloud.

**variables.tf**: This will consist of variables which are used in terraform file.

**terraform.tfstate**: This file has the state information about the managed infrastructure and configuration. As per best practices, this file should be stored in an S3 bucket, but for the demo sake it is kept here in the repo.

**terraform.tfstate.backup**: This file is used by Terraform to keep track of resources and metadata information about the infrastructure.
