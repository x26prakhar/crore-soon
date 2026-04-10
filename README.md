<div align="center">

# CroreSoon

**Free financial planner for Indian households.**
Model your income, taxes, expenses, SIP, and FIRE corpus — and find out how soon you'll hit your crore.

[![Live](https://img.shields.io/badge/live-crore--soon.netlify.app-22c55e?style=flat-square)](https://crore-soon.netlify.app)
[![License](https://img.shields.io/badge/license-MIT-f59e0b?style=flat-square)](LICENSE)
[![No Build](https://img.shields.io/badge/build-none-7c5cfc?style=flat-square)]()

[Features](#features) · [Use It](#use-it) · [Tech Stack](#tech-stack) · [Deploy](#deploy)

</div>

---

## What is CroreSoon?

CroreSoon is a single-file HTML financial planner built for Indian households. Enter your income, expenses, and savings details — it calculates your tax liability, monthly surplus, SIP projections, and tells you when you'll reach your target corpus (₹1 Cr or custom goal).

No signup. No backend. Everything runs in your browser.

---

## Features

- **Income & Tax modelling** — supports both New and Old tax regimes (FY 2025-26)
- **Expense breakdown** — rent, EMIs, lifestyle, insurance, and more
- **SIP projections** — compound growth charts with Chart.js
- **FIRE corpus calculator** — set your goal, see your timeline
- **Excel export** — download your full plan as `.xlsx` via SheetJS
- **OG / WhatsApp sharing** — share your plan link with a rich preview image
- **No install, no build** — single `.html` file, open in any browser

---

## Use It

**Online:** [crore-soon.netlify.app](https://crore-soon.netlify.app)

**Locally:**
```bash
# Just open the file — no server needed
open index.html
```

---

## Tech Stack

| Component | Technology |
|-----------|------------|
| UI | Vanilla HTML, CSS, JavaScript |
| Charts | [Chart.js 4.4.0](https://www.chartjs.org/) |
| Excel export | [SheetJS 0.20.3](https://sheetjs.com/) |
| Build | None — single self-contained HTML file |
| Deployment | Netlify (GitHub-linked, auto-deploy on push) |

---

## File Structure

```
crore-soon/
├── index.html    # Entire app — UI, logic, styles in one file
└── og-image.png  # Social sharing preview image
```

---

## Deploy

Netlify auto-deploys on push to `main`. No build step needed — the `index.html` is served directly.

---

## Data & Privacy

- No backend. No database. No analytics.
- All calculations happen in your browser.
- Nothing is stored or transmitted.

---

<div align="center">
  Built by <a href="https://www.linkedin.com/in/prakharsingh96/">Prakhar Singh</a>
  &nbsp;·&nbsp;
  <a href="https://www.instagram.com/prakhar.vc/">@prakhar.vc</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/x26prakhar/crore-soon">GitHub</a>
</div>
