# Lessons Learned

## Overview

Building this home cybersecurity lab provided hands-on experience with operational security concepts, Linux administration, identity and access management, monitoring, containerized infrastructure, and troubleshooting.

The project emphasized learning through implementation, testing, validation, and problem solving rather than only theoretical study.


# Technical Lessons Learned

## Linux Administration

Working with Ubuntu Server improved understanding of:
- Linux command line usage
- Package management
- Remote administration through SSH
- Service management
- System updates and maintenance


## Docker and Containerization

Deploying services through Docker provided experience with:
- Containerized applications
- Service deployment
- Container lifecycle management
- Persistent data concepts
- Operational troubleshooting
- Resource monitoring


## IAM and MFA

Implementing Authentik improved understanding of:
- Identity and Access Management (IAM)
- Multi-Factor Authentication (MFA)
- OAuth/OIDC authentication workflows
- Authentication vs authorization
- User provisioning
- Administrative access control


## Monitoring and Visibility

Deploying Uptime Kuma reinforced the operational importance of:
- Service monitoring
- Availability validation
- Health checks
- Infrastructure visibility
- Operational awareness
- Troubleshooting workflows


## Reverse Proxy Architecture

Working with Nginx Proxy Manager improved understanding of:
- Reverse proxy concepts
- Internal service routing
- Proxy trust relationships
- Centralized authentication architecture
- Service exposure management


# Operational Lessons Learned

## Troubleshooting Methodology

The lab environment reinforced the importance of:
- Isolating problems methodically
- Testing changes incrementally
- Validating assumptions
- Reviewing logs and service status
- Confirming successful remediation after changes


## Change Management

Implementing updates and integrations demonstrated:
- Importance of validating updates
- Risks associated with major version upgrades
- Operational value of controlled deployments
- Need for rollback awareness
- Service verification after changes


## Network Migration and Recovery

After migrating to Starlink, I validated server connectivity across wired and wireless interfaces, recovered administrative access, verified Docker service health, and confirmed application availability across the environment.

Rather than assuming a single root cause, troubleshooting was performed in layers:

1. Validate operating system access.
2. Verify network connectivity and routing.
3. Confirm Docker service health.
4. Verify container availability.
5. Test application functionality.
6. Validate authentication workflows.
7. Confirm name resolution and reverse proxy functionality.

### Key Lessons

- Infrastructure changes should be validated layer by layer.
- Service availability does not guarantee application accessibility.
- Network routing should be reviewed when multiple interfaces are active.
- Client-side name resolution can cause failures even when backend services are healthy.
- Maintaining alternate access methods can significantly reduce recovery time during troubleshooting.


## Security Mindset Development

The project reinforced several operational security principles:
- Centralized authentication improves administrative security
- MFA reduces credential compromise risk
- Monitoring improves operational visibility
- Access control requires ongoing management
- Security implementations must balance functionality and operational stability


# Professional Growth

The lab environment helped bridge the gap between academic cybersecurity concepts and practical operational implementation.

The project strengthened understanding of:
- Enterprise security concepts
- Operational cybersecurity workflows
- Infrastructure administration
- Technical troubleshooting
- Security focused decision making
- Documentation and technical communication


# Future Goals

Future planned improvements include:
- Expanded service integrations
- Additional MFA protected services
- Cloud infrastructure exposure
- Additional monitoring and logging solutions
- Expanded documentation and architecture diagrams
- Continued development of operational cybersecurity skills
