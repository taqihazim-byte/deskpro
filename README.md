# DeskPro Internal Helpdesk System

DeskPro is a frontend-only internal IT helpdesk demo for Al-Farah Company Iraq.

## Files

- `index.html` — the complete DeskPro app
- `manifest.json` — PWA manifest
- `sw.js` — basic service worker
- `assets/` — app icons

## Default Logins

- Superadmin: `superadmin` / `super@123`
- IT Admin: `admin` / `admin123`
- Supervisor: `supervisor` / `sup123`
- Employee: `emp` / `emp123`
- Demo employee: `samer` / `rep456`

## v5 Features

- IT Dashboard
- Assigned IT Agent and My Assigned / Unassigned filters
- Internal notes hidden from employees
- Suggested priority rules
- Reopen closed ticket with reason
- System Activity Log
- Enhanced Backup / Restore with last backup date
- Print Ticket view
- Notifications with mark-read and clear actions
- Arabic / English UI direction switch per user
- SLA due dates, departments, categories, CSV export, and JSON backup/restore

## GitHub Pages Deployment

1. Create a new GitHub repository.
2. Upload all files and folders from this package to the repository root.
3. Go to **Settings → Pages**.
4. Set Source to **Deploy from a branch**.
5. Select branch **main** and folder **root**.
6. Save and open the published Pages URL.

## Important Limitation

This version uses browser `localStorage` only. Data is stored per browser/device and is not shared between users or devices. For real company-wide production usage, DeskPro needs a backend, database, authentication, and centralized file storage.
