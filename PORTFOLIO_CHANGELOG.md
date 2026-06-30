# Portfolio Changelog

A concise log of portfolio-level improvements across the public GitHub account.

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
