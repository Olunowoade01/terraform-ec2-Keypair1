# terraform-ec2-keypair
Terraform EC2 Instance with key pair and user Data




Step 1 After creating my directory `terraform-ec2-keypair` and running through vsc 
![1](./img/1.png)


# Step 2 adding my `main.tf file `

![2](./img/2.png)

# Step 3 Apply the Configuration using `terraform apply`

![3](./img/3..png)


# Step 4 
- This image shows Terraform configuration and the script added


![4](./img/4%20terraform%20apply.png)


# Step 5 AWS Console – Selecting an AMI
- This image shows the AWS Console where i selected an Amazon Machine Image (AMI) for my EC2 instance.

![5](./img/5.png)

# Step 6  AWS Console – Finding my VPC and Subnet
- This step demonstrates how to find VPC ID and subnet ID in the AWS Console. These values are needed in your Terraform configuration to ensure your EC2 instance is launched in the correct network environment.

![6](./img/6%20correct%20script.png)



# Step 7 Verifying the EC2 Instance and Web Server
- This image shows how to verify that my EC2 instance is running and that the web server is accessible. 

![7](./img/7.png)


## Project Summary
This project demonstrates how to use Terraform to automate the provisioning of an AWS EC2 instance with secure access and automated configuration. The workflow includes generating or using an SSH key pair, creating a security group to allow HTTP access, and launching an EC2 instance with a user data script that installs and starts a web server. The project guides you through best practices for infrastructure as code, including resource management, security, and verification of the deployed environment.