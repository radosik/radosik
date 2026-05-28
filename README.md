<p align="center">
  <img src="assets/banner.svg" alt="Radomyr Moskalenko — full-stack engineer building TypeScript products" width="100%"/>
</p>

<p align="center">
  <img alt="Building: prompt.Prompts" src="https://img.shields.io/badge/building-prompt.Prompts-FF8A4B?style=flat-square&labelColor=0C1322"/>
  <img alt="Based in Alicante, ES" src="https://img.shields.io/badge/based-Alicante%2C%20ES-0EA5E9?style=flat-square&labelColor=0C1322"/>
  <img alt="Stack" src="https://img.shields.io/badge/stack-TypeScript%20%C2%B7%20Next.js%20%C2%B7%20React%20%C2%B7%20Supabase-94A3B8?style=flat-square&labelColor=0C1322"/>
  <img alt="Available for work" src="https://img.shields.io/badge/availability-open%20to%20opportunities-22C55E?style=flat-square&labelColor=0C1322"/>
</p>

## Hi, I'm Radomyr

Full-stack engineer focused on **TypeScript products** — practical AI-assisted tooling, clean UX, and codebases someone else can pick up and ship. Based in Alicante, finishing 1DAW while building a self-hosted decision-support tool for shipment planners.

I care about: a small set of well-chosen primitives over framework soup · multi-tenant data correctness · interfaces that respect the user's time · shipping the audit trail, not just the happy path.

## Featured project

### prompt.Prompts &nbsp;<sub>_current build · private repo, opening at launch_</sub>

> **Write prompts that don't waste tokens.** A studio for authoring AI prompts, seeing exactly where tokens go, and tracking AI provider news — one tab instead of five.

**Stack** — Next.js 16 (App Router, Turbopack) · React 19 · TypeScript 5 · Tailwind v4 · Supabase (Auth + Postgres + RLS) · [`@dnd-kit`](https://dndkit.com) · Framer Motion · [`gpt-tokenizer`](https://github.com/niieani/gpt-tokenizer) (`o200k_base`)

**Four jobs the product does**

- **Compose** — drag-and-drop fragment canvas. Typed snippets (role · goal · constraint · format · example · style · edge_case) with `{{placeholder}}` slots rendered as inline editable pills.
- **Topics** — 8 curated kits (Programming · School · Motion Graphics · n8n · Marketing · Writing · Data Analysis · Roleplay) that retune the picker, fragments panel, and the analyzer's required-kinds set.
- **Analyze** _(the wedge)_ — strength-score gauge (`0.45·coverage + 0.30·specificity + 0.25·efficiency`), "How to reach 100%" checklist, per-fragment token bar, real cost estimate. Local tokenization via `gpt-tokenizer` (`o200k_base`); Anthropic & Gemini exact counts via the providers' `count_tokens` endpoints behind a SHA256 cache.
- **News** — single feed for OpenAI / Anthropic / Google DeepMind / Mistral / Meta AI / xAI / Cohere _(in progress)_.

**Recent shipments** — real per-fragment tokenization · strength-score formula · version-history slide-over with restore · `@dnd-kit` polish with DragOverlay · exact-count server routes for Anthropic + Gemini · settings modal for user-pasted API keys · focus-the-target-fragment auto-scroll.

**Design bar** — Emil Kowalski-tier motion with Linear / Vercel / Anthropic-docs restraint. Quiet greys, a single rainbow conic-gradient accent used sparingly.

Repository opens at launch. Happy to walk through the build if it's relevant to the role.

## Other work

| Project | What it is | Stack |
|---|---|---|
| [Easy-Calculator-Widget](https://github.com/radosik/Easy-Calculator-Widget) — [live demo](https://radosik.github.io/Easy-Calculator-Widget/) | Drop-in calculator widget for embedding | JavaScript |
| [cryptoApi](https://github.com/radosik/cryptoApi) | Crypto market data viewer (CRA) | React · JavaScript |
| [react-finance](https://github.com/radosik/react-finance) · [Finance-Control](https://github.com/radosik/Finance-Control) | Early experiments with personal-finance UI patterns | React · TypeScript |
| [Ballon3D](https://github.com/radosik/Ballon3D) · [dermacorp3D](https://github.com/radosik/dermacorp3D) · [Three-cube](https://github.com/radosik/Three-cube) | Three.js scenes — older work, kept for visual context | Three.js |

## Tech I work with day-to-day

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript" title="TypeScript" width="42" height="42"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" title="JavaScript" width="42" height="42"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" title="React" width="42" height="42"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" title="Node.js" width="42" height="42"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind CSS" title="Tailwind CSS" width="42" height="42"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prisma/prisma-original.svg" alt="Prisma" title="Prisma" width="42" height="42"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" title="PostgreSQL" width="42" height="42"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/threejs/threejs-original.svg" alt="Three.js" title="Three.js" width="42" height="42"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" title="HTML5" width="42" height="42"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" title="CSS3" width="42" height="42"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" title="Docker" width="42" height="42"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" title="Git" width="42" height="42"/>&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="VS Code" title="VS Code" width="42" height="42"/>
</p>

```yaml
Languages: [TypeScript, JavaScript, HTML, CSS, SQL]
Frontend:  [React, Tailwind, shadcn/ui, Radix, Three.js]
Backend:   [Node, Prisma, PostgreSQL, Wasp (TS fullstack DSL)]
Tooling:   [Playwright, i18next, Docker, Mailpit, GitHub Actions]
Interests: [AI-assisted product workflows, multi-tenant SaaS, audio]
```

## GitHub at a glance

<p align="left">
  <img height="195" alt="GitHub streak" src="https://github-readme-streak-stats.herokuapp.com/?user=radosik&hide_border=true&background=0C1322&stroke=0C1322&ring=FF8A4B&fire=FFB976&currStreakLabel=FF8A4B&sideLabels=D7E2F0&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=8A97AD"/>
</p>

### Contribution graph

<!-- A snake "eats" the contribution squares; regenerated every 12h by .github/workflows/snake.yml -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/radosik/radosik/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/radosik/radosik/output/github-contribution-grid-snake.svg"/>
  <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/radosik/radosik/output/github-contribution-grid-snake.svg"/>
</picture>

## Get in touch

Open to full-stack engineering roles — junior or junior-plus, EU-friendly (Alicante-based, comfortable remote or hybrid). I'm most interested in teams shipping product-shaped TypeScript with real users on the other end.

- **Email** — _to be added_
- **LinkedIn** — _to be added_
- **Portfolio** — _to be added_

For project-specific questions, opening an issue on the relevant repo is the fastest path.

---

<sub>This repository is my profile workspace — the source for the banner, the index, and the snippets I reuse in bios elsewhere.</sub>
