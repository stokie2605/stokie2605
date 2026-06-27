# Hi, I'm Dean Wilshaw

Junior Developer focused on DevOps, cloud automation, IT systems tooling, and operational dashboards.

I build practical tools that automate support workflows, surface infrastructure risks, reduce manual checks, and turn operational data into evidence that teams can act on. My portfolio is shaped around the work technical teams deal with every day: cloud cost visibility, scheduled automation, service desk workflows, health checks, reporting, and clean handover documentation.

## Core Toolkit

| Area | Tools and Workflows |
| --- | --- |
| Languages | Python, JavaScript, TypeScript, PowerShell, SQL |
| Cloud and DevOps | Docker, Docker Compose, GitHub Actions, Terraform, AWS automation patterns, Vercel, Firebase Hosting |
| Infrastructure Automation | ECS/Fargate task patterns, EventBridge scheduling, IAM least privilege, CloudWatch-style logging, Trivy scanning |
| Frontend | React, Vite, operational dashboards, responsive UI |
| Backend and Data | Node.js, Firebase, Supabase, SQLite, JSON APIs |
| IT Automation | CLI tools, workstation health checks, report generation, webhook payloads, structured logging |
| Source Control | Git, GitHub, CI/CD workflows, portfolio-grade README documentation |

## Featured DevOps Projects

These are the best starting points if you are reviewing my work quickly.

| Project | What It Solves | Stack | Proof |
| --- | --- | --- | --- |
| [Cloud Cost Guardian](https://github.com/stokie2605/cloud-cost-guardian) | Scans AWS for unattached EBS volumes and idle Elastic IPs, estimates waste, logs for CloudWatch, and can send Discord/Slack alerts. | Python, boto3, Docker, AWS, React, GitHub Actions | [Live demo](https://cloud-cost-guardian-ten.vercel.app) |
| [Cloud-Native Task Automator](https://github.com/stokie2605/cloud-native-task-automator) | Packages a Python health-check task into a Dockerized, Terraform-defined, ECS Fargate scheduled automation pattern with CI/CD and Trivy scanning. | Python, Docker, Terraform, ECS Fargate, EventBridge, GitHub Actions | CI/CD quality gate |
| [Cloud Resource Guard](https://github.com/stokie2605/cloud-resource-guard) | Simulates cloud compliance checks for public SSH/RDP exposure, orphaned resources, and remediation evidence. | Python, CLI, cloud governance | README case study |
| [PowerShell IT Automation](https://github.com/stokie2605/powershell-it-automation) | Demonstrates safe Windows administration automation for workspace setup, disk checks, cleanup simulation, and operational logging. | PowerShell, Windows CLI | Scripted evidence |

## Application and Operations Dashboards

| Project | What It Solves | Stack | Proof |
| --- | --- | --- | --- |
| [Save Our Supper](https://github.com/stokie2605/save-our-supper) | Foodbank referral app where partner agencies submit referrals, staff manage live orders, and collectors can check bag status safely. | React, Firebase Auth, Firestore, Firebase Hosting | [Live app](https://save-our-supper.web.app/) |
| [IT Ticket Dashboard](https://github.com/stokie2605/it-ticket-dashboard) | Service desk dashboard for logging, triaging, resolving, and reviewing internal IT incidents with persistent ticket data. | React, Vite, Supabase | [Live demo](https://it-ticket-dashboard.vercel.app) |
| [Uptime Ping Monitor](https://github.com/stokie2605/uptime-ping-monitor) | Infrastructure monitoring dashboard that simulates polling, outage state, manual recovery, and timestamped event logs. | React, Vite, JavaScript | [Live demo](https://uptime-ping-monitor.vercel.app) |

## Project Highlights

### Cloud Cost Guardian

- Built a Python AWS scanner that uses `boto3` to identify unattached EBS volumes and idle Elastic IP addresses.
- Estimated monthly and annualized waste to make findings useful for FinOps conversations.
- Containerized the scanner so it can run locally or as a scheduled ECS/Fargate-style workload.
- Added CloudWatch-friendly stdout logging and optional Discord/Slack webhook alerts.
- Documented IAM permissions, runtime behavior, and production extension paths.

### Cloud-Native Task Automator

- Built a Python health-check task with structured JSON logs and clear automation-friendly exit codes.
- Packaged the task with a multi-stage Dockerfile and non-root runtime user.
- Declared AWS infrastructure with Terraform, including VPC, IAM, ECS Fargate, CloudWatch logging, and EventBridge schedule components.
- Added a GitHub Actions quality gate for Python linting, Terraform validation, Docker build verification, and Trivy image scanning.
- Documented how the project moves from local script to cloud-native scheduled workload.

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

## Supporting Projects

| Project | Purpose | Stack |
| --- | --- | --- |
| [HN Scraper Task](https://github.com/stokie2605/hn-scraper-task) | Fetches Hacker News HTML, parses story metadata with retry handling, sorts by score, and writes JSON output. | Node.js, Axios, Cheerio |
| [User Provisioning Simulator](https://github.com/stokie2605/user-provisioning-simulator) | Models IAM onboarding logic for usernames, corporate emails, home directories, temporary credentials, and department groups. | React, Vite, JavaScript |
| [IT Support Automation](https://github.com/stokie2605/it-support-automation) | Runs local workstation health checks and produces timestamped support evidence reports. | Python, CLI |
| [MSP Alert Bridge](https://github.com/stokie2605/msp-alert-bridge) | Normalizes raw MSP alert payloads into webhook-ready JSON for routing and triage. | TypeScript, Node.js |
| [IT Asset DB API](https://github.com/stokie2605/it-asset-db-api) | Provides lightweight asset inventory queries using SQLite-backed data. | Python, SQLite |
| [IT Knowledge Base](https://github.com/stokie2605/it-knowledge-base) | Presents internal support documentation in a clean knowledge-base interface. | React |

## How I Build

I try to make projects easy to understand without cloning them first: clear problem statement, visible stack, screenshots or live demos where possible, exact run commands, CI/CD status, and notes about how each prototype could become production-ready.

The common thread across this portfolio is practical operational value: fewer repetitive checks, clearer evidence, better infrastructure visibility, and cleaner handover between IT support, DevOps, and engineering teams.
