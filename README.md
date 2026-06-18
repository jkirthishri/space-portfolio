# Mission Log — An Interactive Career Portfolio

A career portfolio built as a solar system. Instead of a static resume page, every certification, internship, and hackathon I've completed orbits as its own planet — closer and faster-moving bodies represent core milestones (education, internship, hackathon), while a steady outer belt holds my certifications.

**Live site:** https://jkirthishri.github.io/space-portfolio/

## Why I built this

Most "AI/ML project" portfolio gimmicks on LinkedIn look the same — hand-tracking demos, gesture-controlled screens, and so on. I wanted something that actually represents *me* and my journey, not a generic tech demo, while still being a small engineering project in its own right (vanilla JS, CSS keyframe-driven orbits, browser-based persistence).

## What's inside

- **The Sun** — represents me. Click it for a summary of who I am and what I'm looking for.
- **Inner planets** — Education (B.Tech, AI & Data Science), Internship (AVASOFT), and my SIH 2024 Hackathon finalist project (a hardware security system for blockchain wallets, built on Arduino Nano).
- **Outer belt** — every certification I've earned, from AWS Cloud Foundations to Cybersecurity training.
- Each planet opens a detail panel with the full story, dates, and (where uploaded) a certificate image.

## How it works

- Built as a single self-contained `index.html` — no frameworks, no build step, no backend.
- Orbits are pure CSS `@keyframes` animations generated per-planet in JavaScript, so each body moves at its own speed and distance.
- Data (titles, descriptions, images) is stored in the browser's `localStorage`, so I can add new milestones over time without touching code.
- An "Owner mode" toggle (password-protected) lets me add, edit, or remove planets directly from the live page — no redeploy needed for content changes I make locally, though the public link reflects whatever was last pushed here.

## Tech stack

Plain HTML, CSS, and JavaScript. Fonts via Google Fonts (Fraunces, Space Mono). Hosted free on GitHub Pages.

## A note on data

Since this site uses `localStorage`, content I add while testing locally lives only in my own browser. To update what visitors see on the live link, I edit locally, then re-upload the updated `index.html` to this repo.

---

Built by [Kirthishri Jeevanandam](mailto:jkirthishri@gmail.com) — Software Engineer interested in ServiceNow, AWS Cloud, Python, and Generative AI.
