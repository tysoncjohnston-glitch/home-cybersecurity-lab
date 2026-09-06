# MFA and IAM

## Purpose

This security control focuses on centralized identity and access management using Authentik to improve authentication security and administrative access control across the lab environment.

The implementation emphasizes reducing reliance on standalone credentials while improving authentication security through MFA.


# Implemented Controls

Current implementations include:
- Centralized authentication through Authentik
- TOTP MFA enforcement
- OAuth/OIDC integration with Portainer
- User and group management
- Federated login workflows
- Administrative access management
- Break-glass local administrative access retention


# Security Concepts Practiced

- Identity and Access Management (IAM)
- Multi-Factor Authentication (MFA)
- OAuth/OIDC authentication
- Authentication vs authorization
- Centralized identity management
- Administrative access control
- Federated authentication
- User provisioning


# Key Lessons Learned

- MFA significantly improves account security against credential compromise
- OAuth integrations require careful redirect URI configuration
- Authentication and authorization are separate security concepts
- Centralized identity management simplifies administrative security
- Maintaining emergency local administrative access is operationally important
