# BRD Builder

Turn a business need into a Business Requirements Document (BRD) ready for engineering handoff. Built by Cat Nolasco, People Operations.

**Live demo:** https://6aad12668af93a1d8672.agent37.app/brd-builder.html

## What it does

Describe the pain, the process, and the people involved. The builder structures your answers into a complete 12-section BRD, live as you type:

1. Background
2. Problem Statement
3. Goals
4. Scope
5. Stakeholders
6. Current State
7. Proposed Process
8. Requirements (process inputs, process outputs, functional requirements, system dependencies, automation logic, AI usage)
9. Success Metrics
10. Risks and Dependencies
11. Open Questions
12. Engineering Handoff Notes

The output is built for the sections engineering needs to build from: process inputs, outputs, system dependencies, and automation logic. Copy the BRD, download it as Markdown, or print to PDF, all from the page.

## Why this exists

The JD for Blink Health's Sr. Lead, People Operations & Automation role lists hands-on BRD writing as a required qualification, with Workday as the system of record and engineering handoff as a core responsibility. This page is a working demonstration of that skill: it turns a business need into the same structure a People Ops leader would hand to engineering.

The pre-loaded example walks through a real scenario from that world: consolidating payroll inputs across US and India entities into the system of record, with human approval gates and PII-safe AI usage.

## How it works

- Single self-contained HTML file, no dependencies, no build step, nothing to install
- Everything runs in the browser; no data is sent anywhere
- All fonts are self-hosted in `assets/fonts-blink/`
- Brand styling matches the public BlinkRx site (blinkrx.com) by inspection, as a demonstration

## Run it locally

Open `index.html` in any browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Sample data only

All fields are blank until you fill them or load the sample. Sample data is fictional and generic; no real employee or company data is stored or transmitted.

## License

MIT. Fonts are the property of their respective foundries and are included here for demonstration of the brand match.
