# SKSL Connect

Internal employee application for **S. K. Samanta & Co. (P) Ltd.**, Head Office,
Kolkata. People · Culture · Projects.

A single self-contained HTML file. No build step, no dependencies, no server.
Open `index.html` in a browser and it runs.

## What it covers

- **Home** — Across SKSL site-update carousel, project updates, Today at SKSL,
  Good Memories, upcoming holidays, important notices, head office updates
- **Projects** — project pages with milestones, site teams and From Our Sites stories
- **Connect** — company feed, recognition, birthdays, anniversaries, new joiners,
  leadership corner, Pulse polls, ideas, and the Office hub (notices, people,
  departments, policies, contacts, meeting rooms, gallery, learning)
- **My Workspace** — attendance, leave, compensation, documents, requests,
  travel and expenses
- **Profile** — personal details, settings and the HR/admin console

## Running it

Open `index.html` in any modern browser. Sign in with any employee ID.
The compensation section is PIN-protected; the demonstration PIN is `1234`.

## Editing it

See [EDITING-GUIDE.md](EDITING-GUIDE.md) — it maps where the colours, the
content lists and each screen live inside the file.

## Before real use

This build carries sample data and demonstration shortcuts:

- Login accepts any employee ID — connect real authentication
- The salary PIN is hard-coded
- All data is sample data held in the browser's `localStorage`, under the key
  `sksl.connect.v1`. Nothing is sent anywhere and nothing is shared between users.
- Photographs are labelled placeholder slots, not images

**Do not commit real employee data, salary figures or personal information to a
public repository.** A GitHub Pages site is public by default even when the
repository behind it is private.

## Planned integrations

Designed to connect later with SAP/ERP, biometric attendance, Microsoft 365,
payroll software and Primavera P6. None are implemented in this build.
