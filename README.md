
## Secure Hosting via AWS VPC

This project demonstrates how to securely host a simple web application within an isolated and well-architected AWS Virtual Private Cloud (VPC) environment. The infrastructure is designed using AWS networking and compute services, focusing on secure cloud deployment and network segmentation.

### Services Used

* **Amazon EC2** – Hosting the web application instance
* **Amazon S3** – Storage for static files and backups
* **Amazon VPC** – Custom virtual network configuration

  * Public and Private Subnets
  * Route Tables
  * Internet Gateway
  * Transit Gateway
* Security Groups and Network Access Control Lists (NACLs)

### Architecture Overview

The project includes:

* A custom VPC with properly segmented public and private subnets
* EC2 instance deployed in a secure subnet
* Controlled inbound and outbound traffic via Security Groups
* Route tables configured for secure internet access
* Internet Gateway for public connectivity
* Transit Gateway for scalable network architecture
* S3 bucket configured with secure access policies

### Security Implementation

* Principle of Least Privilege
* Restricted inbound ports
* Private subnet isolation
* Secure S3 bucket permissions
* Controlled routing configuration

### 🎯 Objective

To demonstrate practical implementation of secure cloud hosting using AWS networking fundamentals while maintaining best practices in cloud security and infrastructure design.

---

