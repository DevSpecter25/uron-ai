<div align="center">

# ⚡ Uron.ai

**Free AI platform with human-like chat and live code generation.**  
Built from scratch, in public, by one person learning every step of the way.

[![Status](https://img.shields.io/badge/Status-Building%20in%20Public-00e5ff?style=flat-square)](./journal)
[![License](https://img.shields.io/badge/License-MIT-2ea043?style=flat-square)](./LICENSE)
[![Free](https://img.shields.io/badge/Free-Forever-7c3aed?style=flat-square)](#)

</div>

---

## What is Uron.ai?

Uron.ai is a free, open-source AI platform with two things built into one:

**Chat** — Talk to an AI that gives precise, human-like answers with memory of who you are. No subscriptions. No limits hidden behind a login.

**Code** — Describe what you want to build. The AI writes the code. You see it render live — like Lovable or v0, but completely free and open source.

---

## How it works

Instead of sending every request to one expensive model, Uron uses a custom routing engine that picks the best free model for each task automatically.

```
Your message
     ↓
Prompt Optimizer  →  rewrites vague input into a clear structured prompt
     ↓
Task Classifier   →  detects what kind of task this is
     ↓
Model Router      →  picks the cheapest model that can handle it well
     ↓
Agent System      →  specialized agents collaborate on the answer
     ↓
Memory System     →  remembers your history and adapts to you
     ↓
Clean Output      →  structured, formatted, actually useful
```

A grammar fix doesn't need GPT-4. A simple explanation doesn't need Claude Opus.  
Uron figures that out so the platform stays free for everyone.

---

## Tech stack

| Layer | Tools |
|---|---|
| Frontend | React, Tailwind CSS, Vite |
| Backend | Python, FastAPI, WebSockets |
| AI Models | OpenRouter, Groq + Llama, Gemini Flash, Mistral |
| Memory | ChromaDB, SQLite |
| Code Preview | Monaco Editor, Sandpack, iframe sandbox |
| Deploy | Vercel + Railway |

---

## My promise to the community

- **Free, always.** Runs on free-tier models. No paywalls, no pro plan, no hidden limits.
- **Open source, fully.** Every line of code is public. Fork it, learn from it, build on it.
- **Built honestly.** Every mistake, confusion, and breakthrough is documented in the journal. This is not a polished tutorial — it's a real build with real struggles.
- **Yours to learn from.** If you want to build something like this yourself, this repo is your blueprint.

---

## Build journal

I document every session in [`/journal`](./journal).  
Each entry covers what I built, what I learned, and what broke me.

The journal is where the daily story lives — this README stays the same.

---

## Phases

| # | Phase | Status |
|---|---|---|
| 00 | Python foundation + GitHub setup | 🔄 In progress |
| 01 | First AI API call via OpenRouter | ⏳ Upcoming |
| 02 | Prompt optimizer | ⏳ Upcoming |
| 03 | Task classifier | ⏳ Upcoming |
| 04 | Model router | ⏳ Upcoming |
| 05 | Agent system | ⏳ Upcoming |
| 06 | Memory system | ⏳ Upcoming |
| 07 | Chat UI | ⏳ Upcoming |
| 08 | Code generation engine | ⏳ Upcoming |
| 09 | Live preview sandbox | ⏳ Upcoming |
| 10 | Polish + public launch | ⏳ Upcoming |

The only thing that changes here is the status column — and only when a phase is done.

---

## Run locally

> Instructions will be added as each phase is completed.

---

<div align="center">

*Built with curiosity. Documented with honesty. Free for everyone.*

⭐ Star to follow the journey

</div>
