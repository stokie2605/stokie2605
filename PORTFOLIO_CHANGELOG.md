# Portfolio Changelog

A concise log of portfolio-level improvements across the public GitHub account.

## 2026-07-09

### Automated Workflows & Security Hardening

- **Hacker News Daily Signal Pipeline:** Implemented automated GitHub Pages static report deployment workflow in CI running daily via cron.
- **Cloud Cost Guardian:** Built a LocalStack sandbox environment via `docker-compose` with mock resource seeding scripts, custom endpoint injection, and direct React data update paths.
- **Save Our Supper:** Implemented a Vitest security rules test suite, running inside a private CI emulator environment on every push.
- **Website Signal Scanner:** Added a Playwright PDF report generation backend, dynamic frontend printing with print-dialog fallback, and a foodbank audit case study.
- **Cloud Native Task Automator:** Hardened endpoint polling with strict Python-level HTTPS target schema verification to prevent network security group timeouts.
- **Uptime Ping Monitor:** Fixed a state-handling bug in the polling loop that overwrote the transient state of rebooting/offline nodes.
- **User Provisioning Simulator:** Hardened username generation with Active Directory sAMAccountName length limit constraints (20-char limit) and input fallbacks.
- **Visual Presentation:** Replaced the generic visual template montage with a high-fidelity composite graphic showing real screenshots of the `Greasemonkey` and `Ward Tree Services` showcases.

### Portfolio Curation & Anonymization

- Consolidated all static frontend design concepts (including `Alsager Foodbank Showcase` and `David Williams Showcase`) into a single, unified, and anonymized repository: `local-business-design-showcases`.
- Renamed the digital operations project from `digital-ops-con-ed-refresh` to `school-it-support-refresh` and fully anonymized all references to the client name ("Con Ed") to "EduSupport IT" to align with portfolio positioning.
- Added direct code links to `local-business-design-showcases` from the profile README so recruiters can easily review the frontend layout work.

## 2026-07-08

### Profile Reassessment & Project Memory

- Reassessed the main profile README to foreground the strongest current technical projects, including `website-signal-scanner` and `developer-news-signal-pipeline`.
- Removed encoding artefacts and tightened profile copy around IT automation, cloud operations, backend workflows, CI/CD, and safe portfolio tooling.
- Added lightweight `CLAUDE.md` and `TASK-BRIEF.md` project-memory files across active repositories so future AI-assisted work starts from clear project context.
- Replaced the frontend concept montage with a clearer anonymized graphic that matches the listed UI concept categories.

## 2026-07-06

### Portfolio Curation & Cleanup

- Retired and deleted four legacy/outdated repositories to keep the profile focused on core DevOps and IT Automation strengths: `PotterPulse`, `hn-scraper-task`, `it-knowledge-base`, and `serverless-support-bot`.
- Updated the main profile `README.md` to remove these items from the index.

## 2026-07-05

### Frontend Portfolio Concepts

- Added a recruiter-friendly **Frontend & UI Design Concepts (Mobile-First)** section to the profile `README.md`.
- Documented recent educational frontend concepts covering responsive design, accessibility, local SEO structure, performance, and UI hierarchy.
- Added an anonymized SVG montage to show frontend concept visuals without naming local businesses.
- Replaced specific business names with neutral concept categories such as automotive diagnostics, outdoor response, product gallery, and community access interfaces.
- Kept the wording clear that these are portfolio practice concepts, not commercial client work.

## 2026-06-30

### CI/CD & Automated Testing
- **PotterPulse:** Added `pull_request` triggers targeting `main` to the CI/CD workflow, allowing validation checks to execute against all feature branch pull requests.
- **IT Asset DB API:** Developed a comprehensive unit test suite using `pytest` and `fastapi.testclient` that dynamically patches the database connection to run isolated CRUD and schema constraint validation checks against a temporary SQLite DB. Added the test suite to the GitHub Actions CI pipeline.
- **IT Support Automation:** Created a `pytest` suite mocking operating system platform properties and disk usage configurations to verify PC health reporting and cleanup logs, and integrated it into the GitHub Actions CI pipeline.

### Profile Positioning & Polish
- Documented recent testing and mocking hardening passes inside the profile `README.md`.
- Added the `IT Support Automation` repository to the list of verified supporting projects in the profile index.

## 2026-06-29

### Profile Positioning

- Tightened the profile README around IT automation, cloud operations, DevOps workflows, service desk tooling, and operational dashboards.
- Refocused the Start Here section around six pinned projects:
  - Cloud Cost Guardian
  - Cloud-Native Task Automator
  - Save Our Supper
  - IT Ticket Dashboard
  - Uptime Ping Monitor
  - PotterPulse

### Repository Polish

- Fixed the Hacker News scraper test script so `npm test` runs the real test file.
- Cleaned PowerShell IT Automation README headings for safer rendering across terminals and GitHub views.
- Added reviewer-facing setup and production notes across the pinned repos.
- Closed portfolio roadmap issues after adding concrete documentation artifacts.

### Current Focus

- Keep pinned repos clean and demo-ready.
- Add missing screenshots where they improve fast reviewer understanding.
- Keep open issues reserved for real planned work, not broad portfolio reminders.
