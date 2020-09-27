# Udagram 

Deploy an Instagram-like app network infrastructure and servers using CloudFormation.

The latest deployed version of the app is [here]().

The project contains the following components:

* Network Diagram
* Bash scripts to create and update stacks
* Parameter files (network and servers)
* Network Infrastructure Stack file
  * VPC
  * Public Subnets
  * Private Subnets
  * Internet Gateway
  * NAT Gateways
  * Routing
* Servers Stack file
  * IAM Role S3 Read Only
  * Security Groups
  * Launch Configuration
  * Auto-Scaling Group 
  * Load Balancer with Listener and Listener Rules
  * Target Group with Health Checks
  * Bation Host
