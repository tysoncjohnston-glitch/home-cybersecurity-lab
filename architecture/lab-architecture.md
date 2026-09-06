# Lab Architecture

## Overview

This home cybersecurity lab was built to develop hands-on experience with Linux administration, containerized infrastructure, monitoring, identity and access management, MFA, reverse proxy architecture, and operational security concepts.

The environment is hosted on Ubuntu Server and uses Docker to deploy and manage services.


# Core Infrastructure

## Host System

- Ubuntu Server
- SSH enabled for remote administration
- UFW firewall enabled
- Docker installed for containerized application management


# Containerized Services

## Portainer

Purpose:
- Docker container management
- Administrative visibility into running services
- Container lifecycle management

Security Features:
- Integrated with Authentik using OAuth/OIDC
- MFA protected through Authentik
- Local admin retained as break-glass access


## Uptime Kuma

Purpose:
- Infrastructure and service monitoring
- Health checks for internal services
- Visibility into uptime and availability

Monitoring Examples:
- Internet connectivity
- Internal services
- Reverse proxy availability


## Authentik

Purpose:
- Centralized identity and access management
- MFA enforcement
- OAuth/OIDC identity provider

Implemented Features:
- TOTP MFA
- OAuth integration with Portainer
- User and group management


## Nginx Proxy Manager

Purpose:
- Reverse proxy management
- Internal service routing
- Simplified access to internal applications

Example Usage:
- Reverse proxying Uptime Kuma
- Supporting centralized authentication architecture


# Security Concepts Practiced

- MFA
- OAuth/OIDC
- IAM
- Authentication vs authorization
- Reverse proxy architecture
- Containerized infrastructure
- Patch/update management
- Service monitoring
- Operational troubleshooting
- Break-glass administrative access


# Operational Goals

This lab is intended to provide practical operational cybersecurity experience through hands-on implementation, troubleshooting, monitoring, and administration of enterprise-relevant security concepts and infrastructure.
