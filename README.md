![RIO / vitals](https://github.com/rolandriofrio7-dev/rolandriofrio7-dev/raw/main/rio-vitals-banner.png)

# Hi, I'm Roland 👋

I'm a Hispanic public-health grad now building software. I use my clinical experience to make small, well-tested tools that solve real workflow problems, mostly in and around healthcare. Based in TX.

I build with AI as a collaborator, and I'm open about that. I set the problem, the values, the safety boundaries, and the acceptance criteria, then I review every change before it ships. How that works in practice is further down.

---

### A note on my timeline (read this first)

My public commit history is recent and concentrated. I'm newer to building software in the open than I am to doing serious, high-ticket work following SOPs. I came from running paid media professionally (see below) and went deep on engineering this year, in focused bursts. The graph is short on purpose. I'm early, and I'm not going to pretend otherwise.

What I'd ask you to look at instead is *how* the work is built: real test suites, explicit safety boundaries, deterministic logic, and a reviewable commit history broken into small, verified milestones rather than one big unreviewed dump. The depth is in the engineering, not the tenure.

portfolio → [rolandrio.org](https://rolandrio.org)

---

### What I'm building and learning through prompt engineering

**IO: Caregiver Coordination System.** A full-stack prototype that helps caregivers make sense of fragmented post-discharge information. It organizes care signals, caregiver observations, and an audit history into one reviewable workflow.

- Python / FastAPI backend with a deterministic state-machine workflow and action-level provenance/audit logging
- Typed Next.js / React / TypeScript frontend
- **546 automated tests** (254 backend, 240 component, 52 Playwright end-to-end), plus accessibility, type, lint, and build checks
- Explicit AI safety boundaries keeping system-generated and caregiver-authored content separate
- *Synthetic demonstration data only. A prototype, not a clinical product.*

**Recall: Clinic Call-Cadence Tool.** A deterministic, single-file web tool modeling a real clinic's no-show recovery workflow. It computes each call's due date and status from the appointment date rather than storing it.

- Zero dependencies; runs from a double-click on legacy clinic hardware or as a live GitHub Pages demo
- Cadence logic covered by an automated test suite
- *Synthetic demonstration data only.*

**Signal: Ad Diagnostics Tool.** A fully client-side (no-API) tool that parses campaign CSV exports and flags under-performing campaigns against user-calibrated thresholds, with tolerant, BOM-safe header matching. *In active development.*

**Rio Suite: After Effects Developer Tools.** Five original ExtendScript / JSX ScriptUI panels (30+ one-click tools, an interactive bezier easing editor, procedural HUD generators) with a dockable panel architecture and undo-group wrapping.

---

### How I work with AI

I use Claude Code as an engineering collaborator and pressure-test my thinking against other LLMs, but I own the result:

- I define the product problem, safety boundaries, architecture constraints, and acceptance criteria.
- Generated code is never assumed correct. Each phase is bounded by a file manifest and a stop gate.
- Every change is reviewed through automated tests, browser walkthroughs, accessibility checks, and Git-diff inspection before it's committed.

I'm putting this in writing because I'd rather you know exactly how the work gets made than guess at it.

---

### Marketing & leadership

Before and alongside the code, I've run paid media professionally and built my own studio.

**Luxe Media: Paid Media Director** (Oct 2025 to Jul 2026)

- Ran paid media for high-ticket clients; delivered an 11.25x blended ROAS ($5,759 revenue on $512 spend across 8 ad sets) in week one on a client account.
- Managed client accounts; trained and onboarded new hires on paid-media workflows and reporting.

**Rio Studio: Founder** (2025 to Present)

- Run my own paid media and content-production studio, owning client strategy, campaigns, and creative end-to-end.
- Built and deployed the studio's responsive site (vanilla HTML/CSS/JS, IntersectionObserver, Cal.com booking, Netlify).

Platforms: Meta Ads · TikTok Ads · Google Ads · Shopify · Postscript · SEO

---

### Background

B.S. in Public Health, University of Texas at San Antonio. Completed Anthropic's AI Fluency and Claude 101. Currently building toward human-centered healthcare software.

### Reach me

- Email: <rolandriofrio7@gmail.com>
- LinkedIn: linkedin.com/in/rolandriofrio

## 🛠️ Skills

**Languages**

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) [![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) [![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?logo=html5&logoColor=white)](https://img.shields.io/badge/HTML%2FCSS-E34F26?logo=html5&logoColor=white) [![ExtendScript](https://img.shields.io/badge/ExtendScript%20(JSX)-FF61F6)](https://img.shields.io/badge/ExtendScript%20(JSX)-FF61F6)

**AI tools**

[![Claude](https://img.shields.io/badge/Claude-a73918)](https://img.shields.io/badge/Claude-a73918) [![Claude Code](https://img.shields.io/badge/Claude%20Code-a73918)](https://img.shields.io/badge/Claude%20Code-a73918) [![Claude Cowork](https://img.shields.io/badge/Claude%20Cowork-a73918)](https://img.shields.io/badge/Claude%20Cowork-a73918) [![ChatGPT](https://img.shields.io/badge/ChatGPT-412991?logo=openai&logoColor=white)](https://img.shields.io/badge/ChatGPT-412991?logo=openai&logoColor=white) [![Codex](https://img.shields.io/badge/Codex-412991?logo=openai&logoColor=white)](https://img.shields.io/badge/Codex-412991?logo=openai&logoColor=white) [![NotebookLM](https://img.shields.io/badge/NotebookLM-4285F4)](https://img.shields.io/badge/NotebookLM-4285F4) [![Gemini](https://img.shields.io/badge/Gemini-4285F4?logo=google&logoColor=white)](https://img.shields.io/badge/Gemini-4285F4?logo=google&logoColor=white) [![Nano Banana](https://img.shields.io/badge/Nano%20Banana-FFD43B)](https://img.shields.io/badge/Nano%20Banana-FFD43B) [![Perplexity](https://img.shields.io/badge/Perplexity-20B2AA)](https://img.shields.io/badge/Perplexity-20B2AA) [![Stitch](https://img.shields.io/badge/Stitch-4285F4?logo=google&logoColor=white)](https://img.shields.io/badge/Stitch-4285F4?logo=google&logoColor=white)

**Frameworks & tools**

[![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) [![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) [![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) [![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white)](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white) [![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white)](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white) [![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) [![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?logo=visualstudiocode&logoColor=white)](https://img.shields.io/badge/VS%20Code-007ACC?logo=visualstudiocode&logoColor=white) [![Netlify](https://img.shields.io/badge/Netlify-00C7B7?logo=netlify&logoColor=white)](https://img.shields.io/badge/Netlify-00C7B7?logo=netlify&logoColor=white) [![Shopify](https://img.shields.io/badge/Shopify-7AB55C?logo=shopify&logoColor=white)](https://img.shields.io/badge/Shopify-7AB55C?logo=shopify&logoColor=white) [![Postscript](https://img.shields.io/badge/Postscript-1b1c19)](https://img.shields.io/badge/Postscript-1b1c19)

**Creative & productivity**

[![After Effects](https://img.shields.io/badge/After%20Effects-9999FF?logo=adobeaftereffects&logoColor=black)](https://img.shields.io/badge/After%20Effects-9999FF?logo=adobeaftereffects&logoColor=black) [![Premiere Pro](https://img.shields.io/badge/Premiere%20Pro-9999FF?logo=adobepremierepro&logoColor=black)](https://img.shields.io/badge/Premiere%20Pro-9999FF?logo=adobepremierepro&logoColor=black) [![Microsoft Office](https://img.shields.io/badge/Microsoft%20Office-D83B01?logo=microsoftoffice&logoColor=white)](https://img.shields.io/badge/Microsoft%20Office-D83B01?logo=microsoftoffice&logoColor=white)
