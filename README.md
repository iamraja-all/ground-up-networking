# Ground Up — Networking

An interactive, self-paced course that teaches networking from first principles — the real foundation of DevOps. You don't memorize concepts; you hit a wall, **predict** the fix, test it, and see *why* it works. Every lesson ends by creating the need for the next, so the whole path reads as one continuous story.

**Live site:** https://iamraja-all.github.io/ground-up-networking/ _(available a minute or two after the first Pages build)_

## Lessons
1. **Firewalls** — how computers decide who gets in
2. **DNS** — turning names into numbers
3. **HTTPS & TLS** — talking privately over a public wire
4. **Reverse Proxies** — one front door for many apps
5. **CGNAT** — when you don't even have a public IP
6. **VPNs** — a private tunnel across the Internet
7. **Cloudflare Tunnel** — going public with no open ports

Each lesson has gated predictions (you can't skip ahead without committing a guess), retrieval drills, a hands-on **simulator**, and **playable diagrams** — press ▶ Play to watch a packet, a DNS lookup, or the TLS handshake animate step by step.

## Run it
It's a single, self-contained HTML file — no build step, no dependencies.

- **Locally:** open `index.html` in any browser. It works fully offline; your progress saves in that browser via `localStorage`.
- **Host it:** any static host works. This repo is configured for **GitHub Pages**, which serves `index.html` at the site root.

## Tech
Vanilla HTML/CSS/JS, hand-authored inline SVG diagrams, `localStorage` for progress. No frameworks, no external requests, light/dark theme aware.
