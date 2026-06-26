# Hi, I'm Dean Wilshaw | Junior Developer focused on IT Automation, Cloud Tools and Operational Dashboards

I build practical tools that automate support workflows, surface infrastructure risks, and turn operational data into useful dashboards. My projects focus on the kind of work technical teams deal with every day: reducing manual checks, improving visibility, documenting evidence, and making operational workflows easier to run.

## Core Toolkit

| Area | Tools and Workflows |
| --- | --- |
| Languages | Python, JavaScript, TypeScript, PowerShell, SQL |
| Frontend | React, Vite, operational dashboards, responsive UI |
| Backend and Data | Node.js, Firebase, Supabase, SQLite, JSON APIs |
| Cloud and DevOps | Docker, Docker Compose, Firebase Hosting, Vercel, cloud governance simulations |
| Automation | CLI tools, health checks, report generation, webhook payloads, structured logging patterns |
| Source Control | Git, GitHub, deployment-ready README documentation |

## Featured Projects

These are the best starting points if you are reviewing my work quickly.

| Project | What It Solves | Stack | Proof |
| --- | --- | --- | --- |
| [Cloud Cost Guardian](https://github.com/stokie2605/cloud-cost-guardian) | Detects simulated cloud cost waste and public exposure risks, then exports technician-ready JSON/Markdown reports and presents findings in a React dashboard. | Python, React, Vite, Docker, JSON | [Live demo](https://cloud-cost-guardian-ten.vercel.app) |
| [Save Our Supper](https://github.com/stokie2605/save-our-supper) | Foodbank referral app where partner agencies submit referrals, staff manage live orders, and collectors can check bag status safely. | React, Firebase Auth, Firestore, Firebase Hosting | [Live app](https://save-our-supper.web.app/) |
| [IT Ticket Dashboard](https://github.com/stokie2605/it-ticket-dashboard) | Service desk dashboard for logging, triaging, resolving, and reviewing internal IT incidents with persistent ticket data. | React, Vite, Supabase | [Live demo](https://it-ticket-dashboard.vercel.app) |
| [Uptime Ping Monitor](https://github.com/stokie2605/uptime-ping-monitor) | Infrastructure monitoring dashboard that simulates polling, outage state, manual recovery, and timestamped event logs. | React, Vite, JavaScript | [Live demo](https://uptime-ping-monitor.vercel.app) |

## Project Highlights

### Cloud Cost Guardian

- Built a Python scanner that generates mock AWS/Azure-style infrastructure data and detects cost, security, and utilization findings.
- Exported both Markdown reports for technician handover and JSON summaries for automation pipelines.
- Connected scanner output to a React dashboard so the UI reflects structured backend data instead of hardcoded cards.
- Added Docker and Docker Compose support for repeatable report generation.

### Save Our Supper

- Built a Firebase-backed referral workflow with role-based views for pending users, active volunteers, and admins.
- Implemented a live queue for referral intake, acceptance, ready-for-collection status, collection logging, and 24-hour archive review.
- Added a public phone-based status lookup without exposing the full operational queue.
- Documented the Firestore collections, security model, and deployment workflow.

### IT Ticket Dashboard

- Built a React service desk app for creating, categorizing, prioritizing, and resolving IT tickets.
- Added Supabase-backed persistence with fallback demo data so the app stays reviewable even without backend availability.
- Separated active incidents from resolved history and required resolution notes before closure.
- Documented the ticket lifecycle and expected database model.

### Uptime Ping Monitor

- Built a browser-based infrastructure monitoring console with simulated polling and latency drift.
- Added offline asset handling, manual reboot workflow, recovery state, and timestamped event logging.
- Prevented polling updates from overwriting assets during manual recovery states.
- Documented the monitoring state model and production extension path.

## Supporting Projects

| Project | Purpose | Stack |
| --- | --- | --- |
| [HN Scraper Task](https://github.com/stokie2605/hn-scraper-task) | Fetches Hacker News HTML, parses story metadata with retry handling, sorts by score, and writes JSON output. | Node.js, Axios, Cheerio |
| [User Provisioning Simulator](https://github.com/stokie2605/user-provisioning-simulator) | Models IAM onboarding logic for usernames, corporate emails, home directories, temporary credentials, and department groups. | React, Vite, JavaScript |
| [PowerShell IT Automation](https://github.com/stokie2605/powershell-it-automation) | Demonstrates safe Windows workstation setup, disk checks, cleanup simulation, and operational logging. | PowerShell |
| [IT Support Automation](https://github.com/stokie2605/it-support-automation) | Runs local workstation health checks and produces timestamped support evidence reports. | Python, CLI |
| [Cloud Resource Guard](https://github.com/stokie2605/cloud-resource-guard) | Simulates cloud compliance checks for public exposure, orphaned resources, and remediation evidence. | Python, CLI |
| [MSP Alert Bridge](https://github.com/stokie2605/msp-alert-bridge) | Normalizes raw MSP alert payloads into webhook-ready JSON for routing and triage. | TypeScript, Node.js |
| [IT Asset DB API](https://github.com/stokie2605/it-asset-db-api) | Provides lightweight asset inventory queries using SQLite-backed data. | Python, SQLite |
| [IT Knowledge Base](https://github.com/stokie2605/it-knowledge-base) | Presents internal support documentation in a clean knowledge-base interface. | React |

## How I Build

I try to make projects easy to understand without cloning them first: clear problem statement, visible stack, screenshots or live demos where possible, local run commands, and notes about how the prototype could become production-ready.

The common thread across this portfolio is practical operational value: fewer repetitive checks, clearer evidence, better infrastructure visibility, and cleaner handover between IT support, DevOps, and engineering teams.
