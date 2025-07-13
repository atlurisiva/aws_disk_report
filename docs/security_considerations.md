# Security Considerations

## Overview
This document addresses security practices for the solution.

## Key Measures
- Use IAM roles instead of access keys for secure access.
- Implement S3 bucket policies to control access.
- No SSH keys or open inbound ports: All collection uses SSM
- Secrets managed in AWS Secrets Manager only
- Centralized, secure, and versioned reporting in S3
- Role-based Ansible code for modularity and clarity
- IAM best practices enforced
