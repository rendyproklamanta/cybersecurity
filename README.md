# Tools

## OS Hardening

- ufw
- fail2ban
- denyhost
- auditd
- change SSH port
- disable root login
- create user as sudo
- (optional) enable Google Authenticator for all users
- (optional) allow only from specific IP address

## Deployment

- Docker Swarm : for production use and good for isolation source code
- Kubernetes
- letsencrypt : for automatic free SSL

## IDS/IPS

- modsecurity
- crowdsec
- wazuh-agent

## SIEM

- wazuh-manager
- ELK Stack
- splunk

## MySQL

- mariaDB + maxscale : master-slave replication
- SSL enabled
- Encryption table

## NginX

- disable TLS1.0
- enable only TLS1.1 & TLS1.3
- always redirect to SSL (https)
- add_header for security

## Secerets management
- docker secrets
- kubernetes secrets
- hashicorp vault
