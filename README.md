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

**Adversarial code review that escapes AI confirmation bias.** When you ask the same LLM that wrote your code to review it, you get a rubber stamp — it stays in the cognitive track that produced the bug. full-review runs one persistent LLM session through nine sequential passes (taxonomy scan → six focused perspectives → sweep → merge), then hands the code to a different model family for cross-family review (Claude wrote it → Codex and Gemini tear it down). **0.80–0.87 recall on a 15-bug production fixture vs 0.40 for the "five parallel specialists" pattern most plugins ship.** ~110 abstract bug patterns at launch, self-improving — every bug found becomes a pattern. Installs as a Claude Code plugin or a Codex CLI skill. Ships the full benchmark harness; reproduce the numbers on your own fixtures with any LLM.

### 📌 [ax-headers](https://github.com/Oldrich333/ax-headers) — public

**One-line machine-readable headers that cut AI context bloat by ~30 %.** Your AI assistant flies blind through codebases — it burns thousands of tokens opening files just to figure out what they are. ax-headers is one dense line on line 1 of every Python file: `# AX: TAG | SUM: purpose | SIG: version-tag`. The agent reads the directory list, sees each file's role and behavior version, and only loads the body when the task demands it. **~350-file production codebase, measured ~30 % reduction in triage-task context tokens.** Grep-friendly architecture (`grep -l '^# AX: CONN'` lists every connector) turns docs-drift into a non-problem. Ships a bash pre-commit hook, a five-check lifecycle spec, and zero dependencies.

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

