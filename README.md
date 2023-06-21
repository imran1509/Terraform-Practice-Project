# Terraform-AWS-Practice-Project
## This repository contains a terraform file main.tf in which we are doing following steps for our AWS EC2 instance
- create a vpc
- create internet gateway
- create custom route table
- create a subnet
- associate subnet with route table
- create security group to allow port 22,80,443
- create a network interface with an ip in the subnet that was created in step 4
- Assign an elastic IP to the network interface created in step 7
- Create ubuntu server and install/enable pache2
