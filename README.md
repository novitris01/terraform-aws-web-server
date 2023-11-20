# Terraform AWS Web Server

This Terraform configuration sets up an AWS infrastructure to host a basic web server. It includes the creation of a VPC, subnet, internet gateway, security group allowing traffic on ports 22, 80, and 443, an Ubuntu web server instance with Apache2 installed, and associated resources.

## Prerequisites

- [Terraform](https://www.terraform.io/downloads.html) installed
- AWS credentials configured

## Usage

1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd terraform-aws-web-server

2. Initialize Terraform:

   ```bash
   terraform init
   
3. Review and apply the Terraform configuration:

   ```bash
   terraform apply

4. Access the web server:

Open a web browser and enter the public IP address provided in the Terraform output.

## Clean up

Destroy the infrastructure:

    ```bash
    Copy code
    terraform destroy
    Enter 'yes' when prompted.

### Outputs

- server_public_ip: Public IP address of the web server.
- server_private_ip: Private IP address of the web server.
- server_id: ARN of the web server instance.
      
   
