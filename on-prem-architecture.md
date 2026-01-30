# On-Premises Solution Design

## Scenario Overview
The retail company runs all services inside its own data center using physical servers and locally managed infrastructure.

## Components
- Monolithic web application hosted on physical servers
- SQL database server
- Local file storage system
- Company-managed routers and firewalls
- On-premises email server for customer notifications

## Architecture Description
Users access the system through the internet, passing traffic through a firewall and router before reaching the web server. The web server communicates with the database, file storage, and email server internally.

## Components to Be Migrated

| Component | Possible Cloud Model |
|---------|---------------------|
| Web Application | PaaS / IaaS |
| Database | PaaS / IaaS |
| File Storage | PaaS / IaaS |
| Networking | Cloud-native |
| Email Service | SaaS |
