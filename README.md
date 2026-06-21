# sopvoiditem

Interactive POS void item control dashboard for Montauk Holding — ADGM governance framework.

## Features

- **8-Step Void Item Control Lifecycle** — Clickable flowchart with role-based filtering
- **Step Inspector** — Audit guardrails, checklists, and required documents per step
- **Void Authorization Checker** — Interactive simulator for threshold and manager-approval rules
- **Compliance Namer** — YYYYMMDD standardized void log naming tool

## Run locally

Open `index.html` in a browser, or serve with any static file server:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## Deploy

This is a static HTML project. Deploy to GitHub Pages by enabling Pages on the `main` branch with `/ (root)` as the source.
