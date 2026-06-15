# PlayerFinder 🏐
**Scout Smarter. Find Better.**

Professional volleyball scouting platform — runs entirely in the browser, no installation or server required.

---

## Quick Start

Download `index.html` and open it in any browser. That's it.

Or host it online and share the link — see [Hosting](#hosting) below.

---

## Login

| User | Password | Access |
|------|----------|--------|
| `Demo` | `PlayerFinder` | Full scouting app |
| `admin` | `admin2025` | Admin panel (God Mode) |

New users can self-register. Registrations appear in God Mode for approval.

---

## Features

- Filter players by position, status, EU passport, league or keyword
- Priority lists with ratings (1–10) and selection mode
- 3 view modes — List / Cards / Grid
- Player profiles with stats, career, agent info and video links
- Export to CSV, Excel or PDF
- Teams and agents tabs
- Collapsible sidebar, fully responsive (desktop + mobile)
- Admin dashboard to manage users and registrations
- Multi-language: EN / ES / IT / ΕΛ

---

## Hosting

| Option | How |
|--------|-----|
| **Netlify** | Drag `index.html` to [netlify.com/drop](https://netlify.com/drop) — live in 30 seconds |
| **GitHub Pages** | Push to a repo, enable Pages in Settings |
| **GoDaddy** | Upload `index.html` to `public_html/` via File Manager |

---

## Data

All data is stored locally in the browser (`localStorage`). Nothing is sent to any external server. Each user's session is private to their own device.

> Cloud sync across users and devices can be added as a future step.

---

## Tech

Single HTML file — no frameworks, no dependencies, no build step.
Optional: Anthropic Claude API for automatic player import from Volleybox URLs.

---

*Built for OPE Rethymno Volleyball Club — Greek League A1, 2025/26.*
