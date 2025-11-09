# Task Buddy — Prototype (Single‑File)

This is a self‑contained prototype you can open by double‑clicking `index.html`.
No server, no installs. It uses localStorage in your browser to save tasks.

## Open & Run
- Windows/macOS/Linux: double‑click `index.html`.
- Optional: use the provided launcher scripts to open in your default browser:
  - `RUN_WINDOWS.bat`
  - `RUN_MAC.command` (Right‑click → Open if Gatekeeper prompts)

## What’s Inside
- **Task model**: title, due date, priority, impact, effort, estimate, description, status.
- **Scoring**: `(Impact × Priority × Urgency) / Effort`.
- **Urgency**: grows as due date approaches; overdue tasks get extra weight.
- **Auto‑Plan My Day**: choose focus hours and the app fills blocks from high‑score tasks.
- **CSV Export**: download your tasks.

## Notes
- Data stays in the browser where you open it (localStorage).
- This is a front‑end demo; no AI API calls or servers required.
