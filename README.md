# terraform-aws-asg
Problem Statement: 
In order to automate the application deployment process, we need to modularize terraform code that builds multiple components of auto scaling group. 

Goal:
Implement terraform module for above requirements 


Acceptance Criteria:
	1. Make sure it is shareable between teams
	2. Tags are propogated between instances
	3. Security groups should be managed from 1 resource
