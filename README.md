# Oldřich Dvořák 👋

> *Visionary grounded in reality. Lost everything to find the real.*
> *Bridging Tech, Soul & Biology. I ignite fires, not spreadsheets.*
> *Building systems thatv heal.*

🌍 **Highlands roots · Global reach · Czech Republic 🇨🇿**

[![X](https://img.shields.io/badge/X-%40Oldrich333-000000?style=flat-square&logo=x)](https://x.com/Oldrich333)
[![raisin](https://img.shields.io/badge/Project-raisin%20🍇-8B4789?style=flat-square)](https://github.com/Oldrich333/raisin)
[![full-review](https://img.shields.io/badge/Project-full--review%20🔍-44cc11?style=flat-square)](https://github.com/Oldrich333/full-review)
[![ax-headers](https://img.shields.io/badge/Project-ax--headers%20📌-4A90E2?style=flat-square)](https://github.com/Oldrich333/ax-headers)

---

## The work

I build **AI agent systems** — not demos, not benchmarks for their own sake, real systems that run, remember, decide, and ship work. The common thread across everything I make: **treating AI agents as first-class citizens**, not as tools that bolt onto human workflows.

### 🍇 [raisin](https://github.com/Oldrich333/raisin) — public

A methodology and Claude Code skill that lets LLMs write Python for themselves instead of mimicking human conventions. **~50 % fewer tokens, 100 % same functionality.** Verified by 786 tests across six experiments on Click, Flask, Bottle, and greenfield programs.

The point isn't compression for its own sake. The point is: when you stop making the LLM copy human ceremony, you see what the LLM actually wants to write — and it's faster, cleaner, and denser. raisin is the first measurable proof of that.

### 🔍 [full-review](https://github.com/Oldrich333/full-review) — public

Code review skill for Claude Code and Codex CLI. Where most agent-based reviewers stall around 0.40 recall (five parallel specialists each doing a shallow pass), a **single persistent LLM session running nine sequential turns** — taxonomy scan → six focused perspectives → sweep → merge — hits **0.80–0.87 recall on a 15-bug benchmark**.

The path from 0.40 to 0.80 was not obvious. v1 parallel specialists were worse than one smart prompt. v3 checklist (taxonomy-in-prompt) added 50 %. v4 unified_harness (persistent session, categories as separate turns) got the rest. Ships with the full benchmark harness — reproducible on any fixture with any LLM. Pairs with ax-headers.

### 📌 [ax-headers](https://github.com/Oldrich333/ax-headers) — public

One-line machine-readable header on every Python file: `# AX: TAG | SUM: one-line summary | SIG: version-tag`. Tells an LLM what the file is and what version of behavior it encodes — **before the file is opened**. Deployed across ~350 files in production; cut agent triage context usage by ~30 %. A tiny convention with outsized effect on how agents navigate a codebase. Pairs with raisin (dense authoring style) and full-review (catches AX drift during review).

### 🧠 Atlas — in development

Orchestrated intelligence. Dozens to hundreds of AI "brains" collaborating the way a multidisciplinary research institute would. Not a chatbot, not a single large model with tools — an *institute of models* with governance, memory, specialisation, and long-horizon goals. A path toward AGI/ASI through collective intelligence, not a bigger transformer.

### 🐝 Hive — in development

The firm OS. Autonomous business operations where AI agents run the day-to-day — customer work, research, decisions, coordination. Built on graph-powered context and persistent institutional memory. The thesis: a 100-agent team running 24/7 with perfect memory beats a 100-person team who forgets.

### 📚 HCA — in development

One shapeshifter brain, N skill packs, accumulated memory, KPI-driven continuity. A cognitive OS for sustained multi-step work where context matters more than raw model size. Domain-agnostic: a book, a business, a research mission — anything that needs to think over weeks, not seconds.

---

## What I think about

The gap between **how LLMs are trained to write code** (imitating humans) and **how LLMs would write code if we let them**. Current LLMs dutifully produce docstrings, type hints, and boilerplate that exist only because humans read source in terminals without IDE hover. None of that serves the LLM that's writing or reading the code.

raisin is one small piece of a larger question: what does software look like when it's made **by and for machine minds**, but still accountable to human goals? Documentation, protocols, conventions, build systems, debugging workflows — all of these are overdue for a rewrite.

I'm also interested in the softer side: **collective intelligence**, how agents disagree productively, how memory shapes decision-making over time, and where the limits of pure scaling run into the need for structure.

I care about **tech, soul, and biology** — because the interesting problems live at the intersection. Systems that help people heal, systems that remember, systems that take real agency in the real world.

---

## Topics on my mind right now

- **Agent-native architecture** — code, protocols, and infrastructure designed for AI agents from line one, not retrofitted from human conventions
- **LLM-native code** — writing programs for machine reading first ([raisin](https://github.com/Oldrich333/raisin) is the measurable version, [ax-headers](https://github.com/Oldrich333/ax-headers) is the orientation layer)
- **Agent code review as methodology, not magic** — [full-review](https://github.com/Oldrich333/full-review) shows the gap from 0.40 → 0.80 recall is a process choice, not a model upgrade
- **Long-horizon reasoning** — how to make an AI care about a mission across weeks, not just within a conversation
- **Context engineering** — memory, surfacing, compression, retrieval as a design discipline, not an afterthought
- **Collective intelligence** — making 100 agents actually smarter than one, not dumber

---

## Find me

- **X**: [@Oldrich333](https://x.com/Oldrich333) — ideas, half-thoughts, occasional results
- **GitHub**: you're here
- **Email via X DMs** if the conversation is worth having

---

*If you're building agent-native systems, thinking about long-horizon reasoning, or working on the tech/soul/biology intersection — reach out. The work is more interesting when it's shared.*

