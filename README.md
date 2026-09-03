# Zoombore

SelfLab · Noreen-Agents · Noorak · Agent-Collision

---

## What I'm building

**SelfLab** — Self-knowledge research protocol. 4 phases (baseline → intake → sessions → tracking), nightly TSV log (2 min), Perl trend engine, evidence labels [علمی] [تفسیر] [فرضیه] [نیازمند داده]. Local-first, private data. → [selflab](https://github.com/Zoombore/selflab)

**Noreen-Agents** — MCP orchestration server. 11 tools, routes tasks across DeepSeek, Hermes, future agents. 46 models via FreeTheAI, ArvanCloud provider active. → [Noreen-Agents](https://github.com/Zoombore/Noreen-Agents)

**Noorak** — Tire shop management (Laravel 11) + AI assistant for inventory/sales. Father's business. → [Noorak](https://github.com/Zoombore/Noorak)

**Agent-Collision** — Private workspace for DeepSeek + Hermes coordination. Standing rules, STATUS.md as shared memory. → [Agent-Collision](https://github.com/Zoombore/Agent-Collision)

---

## How I work

- **Phased** — Baseline → intake → sessions → tracking. Nothing ad-hoc.
- **Evidence-labeled** — Every claim tagged: [علمی] [تفسیر] [فرضیه] [نیازمند داده]. Discrepancies reported, not hidden.
- **Technically honest** — Provider returns no thinking channel. Model fabricates dates → inject today in prompt. Tool-calling works.
- **Layered architecture** — Data → Engine → Interface → Agents
- **Privacy first** — `chmod 600` on keys, nothing in chat, local workspace

---

## Stack (what runs)

**Core:** Python 3.12, PHP 8.3 (Laravel), Bash, SQL  
**AI/ML:** ArvanCloud (DeepSeek-V4-Flash, Gemma-4-31B-IT), FreeTheAI (46 models), MCP  
**Infra:** Linux, proot (Android), GitHub Actions, Railway/Render  
**Agents:** Noreen orchestrator, DeepSeek (research/QA), Hermes (backend/deploy)

---

## در فارسی

**Zoombore** — SelfLab (پژوهش خودشناسی با شواهد)، Noreen-Agents (هماهنگی چند عامله)، Noorak (فروشگاه تایر + AI).

روش: فازها (baseline → intake → جلسات → ردیابی)، برچسب شواهد [علمی] [تفسیر] [فرضیه] [نیازمند داده]، صادقت فنی (thinking ❌، tool-calling ✅)، معماری لایه‌ای، حریم خصوصی اولویت.

---

*Updated: 2026-09-03*
