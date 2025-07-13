# AWS Disk Utilization Monitoring

## Overview
This project collects disk utilization metrics from EC2 instances across multiple AWS accounts using Ansible.

## Setup Instructions
- Clone the repository.
- Configure the Ansible inventory with your EC2 instances.
- Run the Ansible playbook to collect metrics.
- Use the Python script to aggregate and visualize data.

## Command 
- CMD - (ansible-playbook playbooks/ec2_disk_utilization.yml -i inventories/accounts.yml)

## Documentation
- [IAM Roles and Permissions](docs/IAM_roles_and_permissions.md)
- [Security Considerations](docs/security_considerations.md)
- [Architecture Diagram ] (diagrams/architecture.png)

## New Account addition
- Add new accounts: Edit accounts.yml (ansible\inventories\accounts.yml) and store new credentials in Secrets Manager.
- Add new metrics: Extend or add new roles as needed.# aws_diskutlization
# aws_diskutlization
