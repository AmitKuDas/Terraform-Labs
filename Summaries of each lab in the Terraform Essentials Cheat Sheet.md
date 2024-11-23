### Summaries of each lab in the Terraform Essentials Cheat Sheet

**Lab-1: Creating an EC2 Instance in AWS and Installing Terraform**
- Manually create an EC2 instance in AWS.
- Install Terraform on the EC2 instance.
- Launch an EC2 instance with specific configurations.
- Connect to the EC2 instance securely.
- Create a basic local Terraform configuration to understand Terraform workflow.
- Perform resource cleanup by destroying the created resources.

**Lab-2: AWS EC2 instance creation using Terraform Variables**
- Use Terraform variables to create an EC2 instance.
- Create a Terraform configuration with variables for AWS access keys, secret keys, and the region.
- Create a map variable that dynamically selects the AMI based on the Linux distribution.
- Gain insights into using variables in Terraform configurations.

**Lab-3: Using Output Feature**
- Demonstrate the use of the Terraform output feature.
- Create an EC2 instance and retrieve its public and private IP addresses using Terraform outputs.
- Learn how to extract and display data from Terraform-managed resources.

**Lab-4: Understanding local values, functions and data sources**
- Understand how to declare and use local values.
- Understanding what is function and the different types of functions.
- Understanding data sources and how to use them in configuration files.

**Lab-5: Remote State using Amazon Simple Storage Service (S3)**
- Configure Terraform to store its state file in Amazon S3 as a remote backend.
- Manually create an S3 bucket and configure Terraform to use it for state file storage.
- Emphasize the importance of remote state for collaboration and multi-machine workflows.
- Learn about securing S3 buckets and managing access to them.

**Lab-6: Launching VPC and EC2 Instance**
- Launch a Virtual Private Cloud (VPC) and create subnets using Terraform.
- Configure the VPC, subnets, security groups, and an EC2 key pair.
- Gain hands-on experience in provisioning infrastructure on AWS using Terraform.

**Lab-7: Launching Auto-Scaling Services**
- Create an Auto Scaling Group (ASG) using Terraform.
- Enable dynamic management of a group of EC2 instances based on traffic demand.
- Create CloudWatch alarms to monitor the ASG's performance.
- Simulate increased CPU utilization to observe automatic scaling.
- Understand how to scale infrastructure automatically in response to varying workloads.

**Lab-8: Creating IAM Users and Groups using Terraform**
- Use Terraform to create IAM (Identity and Access Management) users and groups on AWS.
- Define IAM resources, including groups and users.
- Associate users with groups for access control.
- Gain practical experience in managing access to AWS resources using Terraform.

**Lab-9: Creating AWS Resources using Terraform Modules**
- Demonstrate the use of Terraform modules for provisioning AWS resources.
- Deploy resources like VPC, security groups, EC2 instances, and subnets using pre-built modules.
- Simplify infrastructure provisioning by encapsulating resources into reusable modules.
- Focus on module structuring and creating resources efficiently.
