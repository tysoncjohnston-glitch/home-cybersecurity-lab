# Portainer

## Purpose

Portainer is used as the centralized management interface for Docker containers and containerized services within the lab environment.

It provides visibility into:
- Running containers
- Container health and status
- Resource usage
- Networking
- Volumes
- Container logs
- Stack deployments

---

# Security Integration

Portainer was integrated with Authentik using OAuth/OIDC to centralize authentication and enforce MFA for administrative access.

Implemented security features include:
- OAuth/OIDC authentication through Authentik
- MFA enforcement through Authentik
- Automatic user provisioning
- Strict redirect URI configuration
- Retention of local admin credentials as break-glass access

---

# Operational Concepts Practiced

- Container administration
- Centralized authentication
- MFA integration
- OAuth/OIDC implementation
- Role and permission management
- Service monitoring
- Operational troubleshooting
- Administrative access control

---

# Key Lessons Learned

- Difference between authentication and authorization
- Importance of redirect URI security in OAuth
- User provisioning requirements during OAuth integration
- Maintaining emergency local administrative access
- Validating successful service integration through testing and troubleshooting
