# Monitoring

## Purpose

Monitoring was implemented to improve operational visibility, validate service availability, and support troubleshooting across the lab environment.

The goal of monitoring is to identify outages, configuration problems, and service interruptions quickly.


# Implemented Monitoring

Monitoring currently includes:
- Internet connectivity
- Internal service availability
- Reverse proxy accessibility
- Portainer availability
- Authentik availability

Uptime Kuma was configured to perform recurring health checks and validate service responsiveness.


# Security and Operational Concepts

The monitoring implementation provided hands-on experience with:
- Availability monitoring
- Service health validation
- HTTP/HTTPS monitoring
- Infrastructure visibility
- Operational troubleshooting
- Alerting concepts
- Service validation after updates and reboots


# Key Lessons Learned

- Monitoring is critical for operational visibility
- Self-signed certificates can affect monitoring behavior
- Proxy trust settings impact monitoring reliability
- Service validation should occur after configuration changes and updates
- Monitoring assists with troubleshooting and operational awareness
