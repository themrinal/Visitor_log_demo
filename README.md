# SIT Visitor Log — Demo

Live demo of the **VisitorLog** visitor management system built for facility/office use.

**[→ Open Entry Form](index.html) &nbsp;|&nbsp; [→ View Records](visitor-list.html)**

---

## What this demo shows

| Page | What to try |
|------|-------------|
| **Entry form** (`index.html`) | Fill the form, open camera, capture photo, submit — entry is validated but not stored |
| **Records** (`visitor-list.html`) | 12 sample visitors pre-loaded — filter by year/month/purpose, export CSV or PDF |

> Demo mode: no server, no database. All data is hardcoded sample data.

---

## Full version (production)

The real app runs locally on a facility PC with:
- Python `http.server` backend
- Encrypted CSV storage (Fernet / AES-128)
- Password-protected records page
- Auto-start via Windows Task Scheduler
- Custom local URL (`http://visitorlog`)

---

*Built by Mrinal Das — mrinaldas@live.com*
