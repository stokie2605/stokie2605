# Hello, I am Dean.

I am an entry-level developer focused on IT automation, cloud operations, backend workflows, and practical tools for support teams. I build projects that sit between IT support and engineering: automating repetitive checks, modelling operational workflows, tracking infrastructure signals, and making dashboards that help people understand what is happening.

I am currently working toward a full-time IT or developer role, so my portfolio is built around reviewable evidence: clear READMEs, tests, CI workflows, screenshots or live demos where useful, and practical notes about what each project proves.

## Current Focus

- **Operational tooling:** Building small, useful systems for monitoring, alerting, asset tracking, IAM-style provisioning, website checks, and referral workflows.
- **Backend and automation practice:** Strengthening Python, FastAPI, TypeScript, webhook handling, data pipelines, SQLite, Docker, and API-first workflows.
- **CI/CD and project hardening:** Keeping GitHub Actions, tests, validation, safe defaults, and reviewer documentation in place.
- **Portfolio clarity:** Keeping active repositories focused, recruiter-friendly, and easy to inspect without guesswork.

## Start Here

| Project | Why It Matters | Stack | Proof |
| --- | --- | --- | --- |
| [Website Signal Scanner](https://github.com/stokie2605/website-signal-scanner) | Local-first audit assistant that reviews public homepages for SEO basics, accessibility signals, contact clarity, screenshots, sampled link health, and practical report notes. | Node.js, Playwright, HTML, CSS, JavaScript | Safe-mode scanner, report export, CI |
| [Save Our Supper](https://github.com/stokie2605/save-our-supper) | Firebase-backed foodbank referral workflow with role gates, privacy-safe public tracking, Firestore rules, and demo-account isolation. | React, TypeScript, Firebase | [Live app](https://save-our-supper.web.app/) and `Vitest + CI` |
| [Cloud Cost Guardian](https://github.com/stokie2605/cloud-cost-guardian) | AWS FinOps scanner for idle EBS volumes and Elastic IP waste, with dashboard evidence and CI/CD validation. | Python, boto3, Docker, React, GitHub Actions | [Live demo](https://cloud-cost-guardian-ten.vercel.app) and `pytest + CI/CD` |
| [Cloud-Native Task Automator](https://github.com/stokie2605/cloud-native-task-automator) | Scheduled ECS/Fargate task pattern with private AWS service endpoints and blocking image security scans. | Python, Docker, Terraform, GitHub Actions | `pytest` + Terraform + Trivy gate |
| [Uptime Ping Monitor](https://github.com/stokie2605/uptime-ping-monitor) | Infrastructure monitoring dashboard for simulated uptime checks, outage states, recovery actions, and operational logs. | React, Vite, JavaScript | [Live demo](https://uptime-ping-monitor.vercel.app) and `Node test + CI` |
| [Developer News Signal Pipeline](https://github.com/stokie2605/developer-news-signal-pipeline) | API-first backend data pipeline that normalises Hacker News stories, scores developer relevance, and exports SQLite, JSON, and HTML snapshots. | Python, SQLite, pytest, GitHub Actions | Official API usage, tests, CI |

## Engineering Hardening Pass

Recent work has focused on the failure modes that make small projects more realistic:

| Area | Improvement |
| --- | --- |
| Safe scanning | `website-signal-scanner` respects `robots.txt`, skips private/transactional paths by default, caps scan batches, and uses polite delays. |
| Privacy and roles | `save-our-supper` uses role-gated Firestore access, demo-account isolation, and privacy-safe public status lookups. |
| Data integrity | `it-asset-db-api` includes tests around CRUD operations and database behaviour. |
| Runtime resilience | `msp-alert-bridge` normalises alerts and protects outbound webhook forwarding with timeout behaviour. |
| Monitoring workflows | `uptime-ping-monitor` models outage, reboot, recovery, and event-log state transitions. |
| Project continuity | Active repositories now include lightweight `CLAUDE.md` and `TASK-BRIEF.md` files so future AI-assisted work starts from project context. |

## Supporting Projects

| Project | Purpose | Stack |
| --- | --- | --- |
| [StaffRota](https://github.com/stokie2605/staff-rota) | Full-stack shift and rota management system with database-enforced double-booking protection. | Python, FastAPI, React, SQLite, Docker |
| [IT Asset DB API](https://github.com/stokie2605/it-asset-db-api) | FastAPI REST backend for IT asset tracking. | Python, FastAPI, SQLite, Docker, pytest CI |
| [MSP Alert Bridge](https://github.com/stokie2605/msp-alert-bridge) | Normalises MSP alert payloads with shared-secret checks and timeout-guarded webhook forwarding. | TypeScript, Node.js, `Node test + CI` |
| [User Provisioning Simulator](https://github.com/stokie2605/user-provisioning-simulator) | Models IAM onboarding logic for usernames, corporate emails, temporary credentials, and groups. | React, Vite, `Node test + CI` |
| [PowerShell IT Automation](https://github.com/stokie2605/powershell-it-automation) | Windows workstation setup, disk checks, cleanup simulation, and operational logging. | PowerShell, syntax validation CI |
| [IT Ticket Dashboard](https://github.com/stokie2605/it-ticket-dashboard) | Service desk dashboard for logging, triaging, resolving, and reviewing IT incidents. | React, Vite, Supabase |
| [IT Support Automation](https://github.com/stokie2605/it-support-automation) | Windows workstation health checks, disk checks, cleanup simulation, and operational logging. | Python, pytest CI |

## Frontend & UI Design Concepts

Alongside my IT automation and cloud projects, I have built anonymized frontend concepts to practise mobile-first layouts, semantic HTML, accessibility, local SEO structure, fast static pages, and polished interface composition. These are educational portfolio concepts, not client work.

![Anonymized frontend concept montage](assets/frontend-concept-montage.svg)

| Concept Category | Technical Focus |
| --- | --- |
| **Automotive Diagnostics Interface** | Compact information hierarchy, mobile navigation, tap-friendly actions, and fast feedback states. |
| **Outdoor Response Interface** | Theme persistence, urgent action placement, responsive imagery, and readable contrast. |
| **Bespoke Product Gallery Interface** | Visual hierarchy, whitespace, typography pairing, gallery pacing, and product presentation. |
| **Community Access Interface** | Semantic HTML, keyboard-friendly navigation, readable content structure, and a11y-conscious design. |

## Core Toolkit

| Area | Tools and Workflows |
| --- | --- |
| Languages | Python, JavaScript, TypeScript, PowerShell, SQL |
| Cloud and DevOps | Docker, Docker Compose, GitHub Actions, Terraform, AWS automation patterns, Firebase Hosting, Vercel |
| Backend and Data | FastAPI, Node.js, Firebase, SQLite, JSON APIs, webhook payloads |
| Frontend | React, Vite, responsive operational dashboards, accessibility-conscious UI |
| IT Automation | CLI tools, workstation health checks, report generation, monitoring workflows, structured logs |

## How I Build

I try to make each project reviewable without guesswork: clear problem statement, visible stack, exact run commands, tests or CI where practical, screenshots or live demos where useful, and notes about what would be needed for production.

The common thread is practical operational value: fewer repetitive checks, clearer evidence, better infrastructure visibility, and cleaner handover between IT support, DevOps, and engineering teams.

## Portfolio Log

Recent cross-repo polish is tracked in [PORTFOLIO_CHANGELOG.md](PORTFOLIO_CHANGELOG.md).