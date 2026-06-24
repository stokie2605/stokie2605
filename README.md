# Hi, I'm Dean Wilshaw

Welcome to my DevOps & Systems Engineering portfolio.

I build practical tools across **IT Automation**, **Cloud Infrastructure**, and **Data Pipelines**. My projects focus on the kind of work technical teams deal with every day: reducing manual support tasks, improving visibility, detecting infrastructure risk, documenting evidence, and turning raw operational data into useful decisions.

## Portfolio Dashboard

### 🛡️ Cloud Infrastructure & FinOps

| Project | What It Solves | Core Stack |
| --- | --- | --- |
| [cloud-cost-guardian](https://github.com/stokie2605/cloud-cost-guardian) | Detects cloud cost leaks and public exposure risks, then turns them into Markdown, JSON, Dockerized reports, and a React executive dashboard. | Python, React, Vite, Docker, JSON |
| [cloud-resource-guard](https://github.com/stokie2605/cloud-resource-guard) | Simulates cloud compliance checks for public SSH/RDP exposure, orphaned resources, and high-priority remediation evidence. | Python, CLI, Cloud Governance |

### 🤖 Systems & IT Automation

| Project | What It Solves | Core Stack |
| --- | --- | --- |
| [powershell-it-automation](https://github.com/stokie2605/powershell-it-automation) | Demonstrates safe Windows administration automation for workspace setup, disk checks, cleanup simulation, and operational logging. | PowerShell, Windows CLI |
| [it-support-automation](https://github.com/stokie2605/it-support-automation) | Runs technician-style workstation health checks and produces clean evidence logs for repeatable support workflows. | Python, CLI, IT Operations |
| [it-ticket-dashboard](https://github.com/stokie2605/it-ticket-dashboard) | Provides a service desk dashboard for triaging active tickets, reviewing queue metrics, and tracking resolution workflow. | React, Vite, Supabase |
| [user-provisioning-simulator](https://github.com/stokie2605/user-provisioning-simulator) | Simulates IAM onboarding logic including username generation, Active Directory group mapping, and home directory rules. | React, Vite, IAM Logic |

### 📡 Integration, APIs & Data

| Project | What It Solves | Core Stack |
| --- | --- | --- |
| [hn-scraper-task](https://github.com/stokie2605/hn-scraper-task) | Scrapes Hacker News with retry-aware network logic and Cheerio DOM parsing for reliable structured data extraction. | Node.js, Cheerio, HTML Parsing |
| [msp-alert-bridge](https://github.com/stokie2605/msp-alert-bridge) | Normalizes raw MSP alert payloads into clean webhook-ready JSON for routing, triage, and downstream automation. | TypeScript, Node.js, API Workflows |
| [it-asset-db-api](https://github.com/stokie2605/it-asset-db-api) | Provides a lightweight asset inventory backend using SQLite queries to return department-filtered IT asset data. | Python, SQLite, API-style Data |
| [it-knowledge-base](https://github.com/stokie2605/it-knowledge-base) | Presents internal technical documentation in a clean knowledge-base interface for support teams and operational handover. | React, Documentation UI |

## Featured Build: Cloud Cost Guardian

Cloud Cost Guardian is the flagship portfolio project because it brings the whole stack together:

- **Python scanner:** generates mock AWS/Azure-style infrastructure data and detects cost, security, and utilization findings.
- **React dashboard:** visualizes total monthly waste, annualized waste, public exposures, and prioritized remediation status.
- **Docker deployment:** packages the scanner into a repeatable container workflow with host-mounted report output.
- **Dual reporting:** exports both technician-ready Markdown reports and raw JSON summaries for automation pipelines.

## Core Tech Stack

| Area | Tools & Workflows |
| --- | --- |
| Backend & Scripting | Python, Node.js, TypeScript, JSON processing, CLI utilities |
| Frontend Dashboards | React, Vite, searchable tables, operational UI patterns |
| IT Automation | PowerShell, Windows CLI, Linux-style terminal workflows, health checks |
| Cloud & DevOps | Docker, Docker Compose, cloud governance concepts, FinOps simulations |
| Data & APIs | SQLite, webhook payloads, structured API responses, Cheerio HTML parsing |
| Source Control | Git, GitHub, clean commits, portfolio-grade README documentation |

## How I Think About Projects

I like building tools that are easy to run, easy to verify, and easy to explain to both technical and non-technical stakeholders.

The common thread across this portfolio is practical operational value: fewer repetitive checks, clearer evidence, better infrastructure visibility, and cleaner handover between IT support, DevOps, and engineering teams.
