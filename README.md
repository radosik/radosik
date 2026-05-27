<p align="center">
  <img src="assets/banner.svg" alt="Radomyr Moskalenko — full-stack engineer building TypeScript products" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/radosik/RMRoads_Ai"><img alt="Featured: RMRoads AI" src="https://img.shields.io/badge/featured-RMRoads_AI-FF8A4B?style=flat-square&labelColor=0C1322"/></a>
  <img alt="Based in Alicante, ES" src="https://img.shields.io/badge/based-Alicante%2C%20ES-0EA5E9?style=flat-square&labelColor=0C1322"/>
  <img alt="Stack" src="https://img.shields.io/badge/stack-TypeScript%20%C2%B7%20React%20%C2%B7%20Node%20%C2%B7%20Wasp-94A3B8?style=flat-square&labelColor=0C1322"/>
  <img alt="Available for work" src="https://img.shields.io/badge/availability-open%20to%20opportunities-22C55E?style=flat-square&labelColor=0C1322"/>
</p>

## Hi, I'm Radomyr

Full-stack engineer focused on **TypeScript products** — practical AI-assisted tooling, clean UX, and codebases someone else can pick up and ship. Based in Alicante, finishing 1DAW while building a self-hosted decision-support tool for shipment planners.

I care about: a small set of well-chosen primitives over framework soup · multi-tenant data correctness · interfaces that respect the user's time · shipping the audit trail, not just the happy path.

## Featured project

### [RMRoads AI](https://github.com/radosik/RMRoads_Ai)

> Open-source supply-chain disruption response workbench. Rank shipment exception risk, compare recovery options (reroute, expedite, split, notify, wait), and approve the response before delays reach the customer.

**Stack** — [Wasp](https://wasp.sh) (TypeScript fullstack DSL) · React 18 · Tailwind · shadcn/ui · Radix · PostgreSQL · Prisma · i18next · Playwright

**What's in it**
- Deterministic, explainable risk scoring on a shipment exception queue
- Scenario comparison across cost · ETA · customer risk · complexity
- Multi-tenant workspaces — every Prisma write is org-scoped, with invitation flows
- Approve / defer / reject decisions with full audit history and outcome tracking
- Critical-alert email + weekly pilot-summary cron job
- i18n in `en` / `de` / `fr` / `es`, dark-mode default with light-mode parity
- CSV ingest as the only required integration to try it
- OpenSaaS admin panel for pilot leads, tenant health, recommendation log review
- Playwright E2E covering the core decision flow

**Why it's interesting** — decision-support, not autopilot. Humans approve every action; the audit trail is automatic. MIT-licensed, no hosted version, no telemetry, no paid tier.

[**→ Repository**](https://github.com/radosik/RMRoads_Ai)  ·  [**→ Screenshots**](https://github.com/radosik/RMRoads_Ai#screenshots)  ·  [**→ Tech stack**](https://github.com/radosik/RMRoads_Ai#tech-stack)

## Other work

| Project | What it is | Stack |
|---|---|---|
| [Easy-Calculator-Widget](https://github.com/radosik/Easy-Calculator-Widget) — [live demo](https://radosik.github.io/Easy-Calculator-Widget/) | Drop-in calculator widget for embedding | JavaScript |
| [cryptoApi](https://github.com/radosik/cryptoApi) | Crypto market data viewer (CRA) | React · JavaScript |
| [react-finance](https://github.com/radosik/react-finance) · [Finance-Control](https://github.com/radosik/Finance-Control) | Early experiments with personal-finance UI patterns | React · TypeScript |
| [Ballon3D](https://github.com/radosik/Ballon3D) · [dermacorp3D](https://github.com/radosik/dermacorp3D) · [Three-cube](https://github.com/radosik/Three-cube) | Three.js scenes — older work, kept for visual context | Three.js |

## Tech I work with day-to-day

```text
Languages    TypeScript · JavaScript · HTML · CSS · SQL
Frontend     React · Tailwind · shadcn/ui · Radix · Three.js
Backend      Node · Prisma · PostgreSQL · Wasp (TS fullstack DSL)
Tooling      Playwright · i18next · Docker · Mailpit
Interests    AI-assisted product workflows · multi-tenant SaaS · audio
```

## GitHub at a glance

<p>
  <img height="160" alt="Radomyr's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=radosik&show_icons=true&hide_border=true&include_all_commits=true&count_private=false&title_color=FF8A4B&icon_color=FFB976&text_color=D7E2F0&bg_color=0C1322"/>
  <img height="160" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=radosik&layout=compact&hide_border=true&langs_count=8&title_color=FF8A4B&text_color=D7E2F0&bg_color=0C1322"/>
</p>

## Get in touch

Open to full-stack engineering roles — junior or junior-plus, EU-friendly (Alicante-based, comfortable remote or hybrid). I'm most interested in teams shipping product-shaped TypeScript with real users on the other end.

- **Email** — _to be added_
- **LinkedIn** — _to be added_
- **Portfolio** — _to be added_

For project-specific questions, opening an issue on the relevant repo is the fastest path.

---

<sub>This repository is my profile workspace — the source for the banner, the index, and the snippets I reuse in bios elsewhere.</sub>
