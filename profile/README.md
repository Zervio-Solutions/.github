# Zervio Solutions

Fast, reliable infrastructure for game servers, web hosting, automation, and customer operations.

## What we operate

Zervio Solutions builds and maintains the infrastructure behind hosted gaming communities and web services. The organization contains private service repositories for production operations, automation, billing, observability, reverse proxying, documentation, and public-facing websites.

## Core platform areas

| Area | Purpose |
|---|---|
| Game hosting | Pterodactyl-backed game server infrastructure and panel operations |
| Web hosting | Public website, documentation, and customer-facing services |
| Billing | Paymenter-based customer billing and service management |
| Automation | Hermes-powered internal automation, repo synchronization, and AI operations |
| Observability | Uptime checks, service monitoring, health visibility, and alerts |
| Edge routing | Traefik, Cloudflare, SSL, DNS, and reverse proxy operations |

## Repository map

| Repository | Role |
|---|---|
| `admin-zervio` | Main admin platform stack and deployment workspace |
| `admin-panel` | Next.js administrative interface |
| `agent-backend` | Backend service for internal AI/agent operations |
| `website` | Public Zervio Solutions website |
| `docs-zervio` | Documentation site and knowledge base |
| `zervio-discord-bot` | Discord automation and community support bot |
| `paymenter` | Billing and customer service management stack |
| `pterodactyl` | Game server panel/infrastructure stack |
| `traefik` | Reverse proxy and edge routing stack |
| `ops-observability` | Monitoring, update checks, and health visibility |
| `uptime-kuma` | Uptime monitoring stack |
| `n8n` | Workflow automation stack |
| `phpmyadmin` | Database administration utility stack |

## Operational standards

- Infrastructure is Docker-first and deployed from the production host.
- Secrets, certificates, databases, logs, runtime state, and backups stay off GitHub.
- Repositories include generated service READMEs with setup, deployment, and troubleshooting notes.
- Automation keeps service repositories synchronized as new Docker services are added.
- Production changes should be verified with container health checks and service logs.

## Public links

- Website: https://zerviosolutions.com
- Support: support@zerviosolutions.com

---

Private repositories are used for infrastructure and service code. Public content is limited to organization profile and approved customer-facing assets.
