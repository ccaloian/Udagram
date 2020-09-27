# Udagram 

A high-availability Instagram-like app network infrastructure and servers using CloudFormation.

> The latest deployed version of the app is [here](http://udagr-webap-nq25dp9ned3z-2094158975.us-west-2.elb.amazonaws.com/).

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
  * Outputs
* Servers Stack file
  * IAM Role with S3ReadOnly access
  * Security Groups
  * Launch Configuration
  * Auto-Scaling Group 
  * Load Balancer with Listener and Listener Rules
  * Target Group with Health Checks
  * Bation Host
  * Outputs
