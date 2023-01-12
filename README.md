# Terraform AWS

This creates a VPC with CIDR block of 10.0.0.0/16, two subnets one is private and the other is public, each with their own CIDR block and availability zone. Also creates a security group which is acting as firewall and allows only incoming traffic on port 22 (SSH) from anywhere.

You can add more rules to the security group as per your requirement and also add Elastic IP and route tables to make the subnet public and also you can add RDS, EC2 instances and more resources as per your requirement.
