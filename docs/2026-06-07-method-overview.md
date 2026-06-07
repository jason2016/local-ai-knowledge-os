# Local AI Knowledge OS — Method Overview (2026-06-07)

> A local-first, Markdown-based, AI-readable way to keep your projects, decisions, and knowledge in one place — so any AI tool can pick up where you left off.

This document is the public, plain-language introduction to the **Local AI Knowledge OS** and the **Semantic OS Method** that underpins it. It is written for a general GitHub audience: builders, makers, freelancers, small teams, and anyone who works with AI assistants and is tired of re-explaining the same context over and over.

---

## What is a Local AI Knowledge OS?

A Local AI Knowledge OS is a small, opinionated folder structure on your own computer that holds:

- the **raw inputs** you collect (notes, links, snippets, ideas),
- the **distilled meaning** you extract from them,
- the **durable knowledge** you want to keep,
- an **index** that ties everything together,
- your **active projects**, and
- a dedicated **AI System** area that tells AI agents how to read and use the whole thing.

It is:

- **Local-first** — the source of truth lives on your machine (or your own synced folder), not locked inside a single app or cloud service.
- **Markdown-based** — plain text files that you, your editor, your version control, and any AI model can read.
- **AI-readable** — structured and labelled so a model can navigate it without a human translating first.
- **Tool-agnostic** — Claude, Codex, ChatGPT, or a local LLM can all work against the same files.

Think of it as a **second brain that an AI can actually use**, not just a place where you pile up notes.

---

## How it relates to the Semantic OS Method

The **Semantic OS Method** is the internal methodology behind this repository. The short version of the idea:

> Organize information by **meaning and role**, not by app or file type, so that both humans and machines can reason about it.

"Semantic" means each piece of content has a clear **role**: is it raw input, a distilled insight, durable knowledge, a decision, a project map, or system instructions for the AI? When every item knows what it *is*, an AI agent can be told simple, reliable rules like "read the project map first, then the relevant knowledge notes, then propose next actions."

The **Local AI Knowledge OS** is the *public, practical starter kit* version of that method:

- The Semantic OS Method is the **thinking** (the principles).
- The Local AI Knowledge OS is the **starter structure** (the folders, templates, and conventions you can copy today).

The full, detailed method is developed in the companion KDP book *Build Your Local AI Knowledge OS*. This repository intentionally contains only the safe, reusable, public-friendly parts.

---

## The problem: AI tools lose project context

Modern AI assistants are powerful but **forgetful by design**:

- Each new chat starts from zero. You re-paste the same background every time.
- Context windows are limited. Long projects don't fit.
- Different tools (Claude, ChatGPT, Codex, local models) don't share memory.
- Important decisions get buried inside old conversations you can't search.
- Six months later, *you* don't remember why a choice was made — and neither does the AI.

The result is wasted time, inconsistent answers, and AI output that ignores decisions you already made.

The missing piece is not a smarter model. It's a **stable, external memory** that lives outside any single chat — one that you control and that any model can read.

---

## The solution: a local-first, AI-readable knowledge structure

The Local AI Knowledge OS solves this by keeping context in **plain Markdown files with clear roles**, organized so an AI can be pointed at exactly the right material.

The flow is simple:

```
Capture  →  Distill  →  Keep  →  Index  →  Use in projects  →  Feed AI  →  Capture feedback
```

Because everything is local Markdown:

- You own it and can back it up however you like.
- It works offline and with local models.
- It survives any single app shutting down.
- It is diff-able, searchable, and version-controllable.
- Any AI tool can read it without a special integration.

---

## Core components

The OS is made of a handful of clearly-named parts. Each has one job.

| Component | Role | Question it answers |
|-----------|------|---------------------|
| **Inbox** | Raw capture | "What did I just collect?" |
| **Distill** | Processing | "What does this actually mean?" |
| **Knowledge** | Durable notes | "What do I want to keep and reuse?" |
| **Index** | Map / table of contents | "Where is everything?" |
| **Projects** | Active work | "What am I working on, and where does it stand?" |
| **AI System** | Instructions for agents | "How should the AI read and use this OS?" |
| **Context Packs** | Curated bundles | "What does the AI need *right now* for this task?" |
| **Action Feedback** | Loop closure | "What happened when we acted, and what did we learn?" |

A few notes on the less obvious ones:

- **Context Packs** are small, hand-curated (or AI-assembled) bundles of just the files relevant to a specific task. Instead of dumping everything into a chat, you hand the AI a focused pack. This keeps answers grounded and within context limits.
- **Action Feedback** closes the loop. When you act on an AI suggestion, you record what actually happened. Over time this turns the OS into a record of *what works*, not just *what was planned*.

---

## Why this is different from a normal note-taking system

A normal note app optimizes for **humans browsing notes**. The Local AI Knowledge OS optimizes for **humans and AI agents collaborating on work**. The differences:

1. **Role-based structure, not folders-by-topic.** Every item has a semantic role (input, knowledge, decision, project map, system rule). The AI relies on those roles.
2. **Designed to be fed to a model.** Context Packs and the AI System folder exist specifically so an agent can be pointed at the right context cheaply.
3. **Decisions and incidents are first-class.** Templates capture *why* something was decided, so future-you and future-AI don't relitigate it.
4. **A feedback loop is built in.** Outcomes are recorded, so the system gets more useful over time instead of just bigger.
5. **Tool-agnostic and local-first.** It is not tied to one vendor, one cloud, or one model.

A note system stores what you wrote. A Knowledge OS stores **what you decided, why, and how to reuse it** — in a form an AI can act on.

---

## How Claude, Codex, ChatGPT, and local LLMs use it

Because everything is plain Markdown with clear roles, every tool uses the same underlying material — just through its own interface.

- **Claude (Claude Code / desktop / web):** Point it at the repository or paste a Context Pack. The `09_AI_System` folder gives it the rules; the Project Map gives it state; Knowledge notes give it grounding. Claude can read the OS, propose next actions, and draft new records you save back.
- **Codex / coding agents:** Treat the OS as project memory alongside the codebase. The Project Map and Decision Records explain *why* the code looks the way it does; the agent reads them before changing things.
- **ChatGPT (or any chat UI):** Open the relevant Markdown files, paste a Context Pack into the conversation, and the model now has the same grounding as any other tool. No integration required.
- **Local LLMs (Ollama, LM Studio, etc.):** Because the OS is local files, a local model can read them directly with a simple retrieval setup — fully offline, fully private.

The pattern is always the same:

1. Assemble a **Context Pack** for the task.
2. Let the AI read the **AI System** rules + the **Project Map** + relevant **Knowledge**.
3. Act on the output.
4. Record an **Action Feedback** note and update the **Project Map**.

The model changes. The OS stays.

---

## Where to go next

- Copy the [`starter-kit/`](../starter-kit/README.md) structure into your own vault or folder.
- Read each folder's README to learn what belongs where.
- Use the [`templates/`](../templates/) to start recording decisions, incidents, project maps, and context packs.
- See [`examples/sample-project-map.md`](../examples/sample-project-map.md) for a complete, fictional example.
- Browse the [book outline](../book/outline/2026-06-07-book-outline.md) to see where the full method is headed.

> This repository is a **companion resource**, not the full book. It gives you the structure and templates; the book explains the method in depth.
