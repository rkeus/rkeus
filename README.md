### Hi, I'm Uros

Full-stack & AI systems engineer in Belgrade, Serbia. 20+ years of building and running production web systems, from multi-language site networks and a live streaming platform to self-hosted AI infrastructure: RAG, MCP servers and agent tooling.

Founder of [rkeus](https://www.rkeus.com).

#### What I work on

- **AI systems** - RAG platforms, MCP servers, custom agent skills and n8n automation pipelines, running on my own infrastructure with local inference (Ollama), so no data leaves the building.
- **Full-stack** - PHP, Python / FastAPI, JavaScript, React Native, PostgreSQL + pgvector, MySQL.
- **Infrastructure** - Linux, Nginx, Docker, Proxmox, TrueNAS. I run 4 production web servers and 3 on-prem servers. Grafana + Prometheus watch my sites, the network and ISP outages.
- **Technical SEO** - built and ranked 360+ sites across multiple languages; programmatic SEO and AI search (GEO).

#### Selected projects

- **ai-context** - self-hosted RAG platform that gives AI coding agents persistent, searchable memory. Heading-aware chunking, local Ollama embeddings, PostgreSQL + pgvector (HNSW), and keyword search as a fallback when the embedder is down. Served over an MCP server and a FastAPI REST API. In daily use across dozens of my projects.
- **Hermes agent skills** - I run the open-source Hermes agent with my own skills for daily ops: email triage, git activity, Proxmox / infra health. Security is enforced in code, not config: non-GET methods raise before a socket opens, OAuth2 goes through a single scope-validation choke point, and logs are redacted centrally.
- **MILE** - homelab control panel and voice assistant (Node.js / Express): Proxmox containers, Docker, router and WireGuard VPN management, scheduled jobs with an audit log, and an MCP server for agents. Designed by me, built with Claude Code.
- **Radio S** (client work) - streaming platform for 8+ terrestrial and 30+ digital radio stations and live music TV, plus a React Native app shipped on iOS and Android.
- **Fleet management SaaS** (rkeus) - multi-tenant B2B platform for rent-a-car and leasing companies, in testing with client companies.

Repositories are being published here step by step.

#### How I build

For 20 years I wrote all of my code - PHP, JavaScript, SQL, server configs - for client platforms, my own companies and hundreds of sites. Today I build my newer projects with AI coding tools: I own the design, architecture, review, deployment and operation, and Claude Code, Codex and Cursor write much of the code. Two decades of writing it myself is what lets me review, fix and run what they produce.
#### Elsewhere

[LinkedIn](https://www.linkedin.com/in/uros-mutavdzic) · [www.rkeus.com](https://www.rkeus.com)
