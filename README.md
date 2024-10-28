# Implement-Load-Balancing-on-Compute-Engine-for-SMEs
## Project Overview
This project involves provisioning and managing cloud resources to support various teams and their applications. I’ll focus on creating a reliable, cost-effective infrastructure that meets the technical and organizational standards set by Jooli, without relying on step-by-step guidance.

## Objective
In this project, I will:

Set up and manage cloud infrastructure for Jooli, Inc., a small company as per the needs of different teams, particularly the Nucleus team, which has provided an initial set of requirements.
Ensure that all resources are created in the default region and zone unless otherwise specified.
Apply Jooli’s naming conventions and resource standards to ensure consistency and compliance with organizational guidelines.
Standards and Guidelines
Naming Conventions
All resources will be named using the format team-resource. For instance, if I’m setting up a web server for the Nucleus team, I will name it nucleus-webserver1.

Resource Configuration
For Linux virtual machines, I’ll use e2-micro as the default machine type to maintain cost efficiency.
For Windows virtual machines or Kubernetes nodes, I’ll use e2-medium to meet the performance requirements.
Instances requiring a template will be created in the global location for easier management across regions.
Cost-Effective Resource Allocation
Given that project budgets are strictly monitored, I’ll carefully plan resource sizes to prevent excessive use. Jooli, Inc. enforces strict guidelines, and failure to adhere could lead to project termination. Therefore, I’ll ensure all resources are efficiently sized for their purpose, in line with the monitoring team’s guidance.
I set up network load balancers, application load balancers, instances and tested the traffic that are sent to the VMs.

**I will use Google Cloud Platform for this project**, 
**By the end of this project, I’ll have completed several infrastructure provisioning tasks that support Jooli’s cloud infrastructure, aligning with best secure practices and resource management protocols.**
