# Hi, I'm Adithya Kammara

Software engineer in Hyderabad. I build full-stack web apps and AI features, and I care about what happens after the demo: tests, evaluations, CI and accessibility.

By day I'm a **Process Executive at Cognizant**, validating JSON and XML content feeds and debugging ingestion issues for a large media platform. Outside work I build the projects below.

**Looking for:** SDE-1, full-stack or backend roles in Hyderabad, Bengaluru or remote.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-adithyakammara-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/adithyakammara)
[![Email](https://img.shields.io/badge/Email-adithyakammara13%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:adithyakammara13@gmail.com)
[![X](https://img.shields.io/badge/X-@itsadithyak-000000?logo=x&logoColor=white)](https://twitter.com/itsadithyak)

---

## Projects

### [AI Ticketing](https://github.com/AdithyaKammara/ai-ticketing) · [Live demo](https://ai-ticketing-henna.vercel.app)

An internal support desk where an LLM triages each ticket and plain code decides what it's allowed to do. The model suggests a category, severity and draft answer; deterministic guardrails control routing and auto-resolution, and any model failure goes to a person.

- **Measured on 116 hand-labeled tickets:** 97.4% category accuracy, 97.4% routing accuracy, 0 unsafe auto-answers, 10/10 prompt-injection attempts classified correctly
- Async triage on a Redis job queue, role-based access for requesters, agents and admins, and analytics
- 217 backend tests at 97% coverage, plus frontend and Playwright end-to-end tests with accessibility scans
- Written up with a PRD, architecture decision records and a published evaluation report

`Python` `FastAPI` `PostgreSQL` `Redis` `React` `TypeScript` `Docker` `Groq`

<a href="https://github.com/AdithyaKammara/ai-ticketing"><img src="https://raw.githubusercontent.com/AdithyaKammara/ai-ticketing/main/docs/screenshots/dashboard.png" alt="AI Ticketing admin dashboard" width="720"></a>

<sub>The demo runs on a free tier, so the first request after it has been idle can take about a minute.</sub>

### [TaskFlow](https://github.com/AdithyaKammara/taskflow) · [Live app](https://adithyakammara.github.io/taskflow/)

A team task manager with accounts, shared workspaces and live sync: a teammate's change shows up in about a second, with no refresh.

- Dashboard with hand-built SVG charts, list, drag-and-drop board and month/week/list calendar
- Natural-language quick add (`Review PR tomorrow @priya #dev !high`), undo/redo, command palette and keyboard shortcuts
- Row Level Security on every table; workspaces can only be joined through a valid invite
- 73 unit tests and 24 Playwright end-to-end tests, including WCAG 2.1 AA scans in both themes
- Migrated from plain JavaScript to React and strict TypeScript, [documented here](https://github.com/AdithyaKammara/taskflow/blob/main/docs/MIGRATION-V7.md)

`React` `TypeScript` `Supabase` `PostgreSQL` `Zustand` `Playwright`

<a href="https://adithyakammara.github.io/taskflow/"><img src="https://raw.githubusercontent.com/AdithyaKammara/taskflow/main/docs/screenshots/dashboard-light.png" alt="TaskFlow dashboard" width="720"></a>

### [Safarnama](https://github.com/AdithyaKammara/Tourism-Website) · [Live site](https://safarnama-cyan.vercel.app)

Travel guides to India with a trip planner: when to go, what a day really costs in rupees, and an itinerary that turns into days, a budget, a packing list and bookings.

- Drag-and-drop itinerary with a route map, weather for your dates, and calendar (`.ics`) export
- Guests plan in the browser; signing in syncs their trips to an account
- Filters live in the URL, so a filtered list can be shared

`Astro` `React` `TypeScript` `Supabase` `MapLibre` `Tailwind CSS`

### [Food Munch](https://github.com/AdithyaKammara/Food-Munch-) · [Live demo](https://foodmunch-app.vercel.app)

A food-ordering frontend inspired by Hyderabad's food culture: dish search and filters, portion and spice customisation, a persistent cart with promo codes, checkout and a simulated order tracker.

- Cart and order state in Zustand, persisted in the browser
- 48 tests with Vitest; lint, tests and a type-checked build run in CI

`React` `TypeScript` `Vite` `Tailwind CSS` `GSAP` `Vitest`

### [Data Analyst Assignment](https://github.com/AdithyaKammara/Data_Analyst_Assignment)

A hiring assignment for PlatinumRx: schemas and ten analytical queries for hotel and clinic datasets (CTEs, `RANK` and `DENSE_RANK` window functions, monthly profit roll-ups), a ticket-analysis workbook and two Python utilities.

`SQL` `Excel` `Python`

---

## Tech I've shipped with

| Area | Tools |
| --- | --- |
| Languages | TypeScript, JavaScript, Python, SQL |
| Frontend | React, Astro, Vite, Tailwind CSS, Zustand |
| Backend & data | FastAPI, SQLAlchemy, PostgreSQL, Redis, Supabase |
| AI | Groq API, structured LLM output, evaluation sets, guardrails |
| Testing | pytest, Vitest, Playwright, axe |
| Delivery | Docker, GitHub Actions, Vercel, Render, GitHub Pages |

## Experience

**Process Executive**, Cognizant Technology Solutions · Hyderabad · Jul 2025 – present

- Validate large JSON and XML content feeds for a media platform and keep multi-stage ingestion pipelines clean
- Trace failures back to schema drift, data-contract mismatches and API response anomalies, and document the fixes
- Turn partner data specs into ingestion workflows, working across product, data and partner teams

## Education

- B.Tech, Computer Science and Engineering, BIET Hyderabad
- NxtWave CCBP 4.0: full-stack development
