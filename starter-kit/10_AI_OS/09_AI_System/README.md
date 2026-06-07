# 09_AI_System — Instructions for AI Agents

This folder is the **control room** for how AI tools interact with your OS. It holds the rules, conventions, and reusable prompts that tell any model — Claude, Codex, ChatGPT, or a local LLM — how to read your knowledge and how to behave when working on it.

If the rest of the OS is *what the AI reads*, this folder is *how it should read it*.

## What belongs here

- **System rules** — how the OS is structured and how the AI should navigate it
- **Reading order** — e.g. "Index → Project Map → relevant Knowledge → then act"
- **Reusable prompts** — for distilling, drafting decisions, building context packs
- **Output conventions** — file naming, where new records should be saved, link style
- **Guardrails** — what the AI must never do (e.g. never invent decisions, never delete records, never expose secrets)

## What does NOT belong here

- Actual project content → [`06_Projects/`](../06_Projects/README.md)
- Durable knowledge → [`02_Knowledge/`](../02_Knowledge/README.md)
- Secrets, API keys, or private credentials — **never store these in any AI-readable file**

## Suggested files

```
09_AI_System/
├── system-rules.md      # How the OS works + how the AI should use it
├── reading-order.md     # The default navigation order for agents
├── prompts/             # Reusable prompts (distill, decide, pack, review)
└── guardrails.md        # Hard limits the AI must respect
```

## A starting `system-rules.md`

```markdown
# AI System Rules

You are working inside a Local AI Knowledge OS made of Markdown files.

How to work:
1. Start at 03_Index to orient.
2. For project work, read the project's Project_Map.md first.
3. Pull grounding from 02_Knowledge as needed.
4. Use only the provided Context Pack when one is given.
5. When you make or learn something durable, propose a new record
   using the matching template in /templates.

Hard rules:
- Never invent decisions or facts. If unknown, say so.
- Never delete or overwrite existing records; propose changes instead.
- Never read or output secrets, keys, or private client data.
- Always use relative Markdown links for references.
```

## Why it matters

This is what makes the OS **tool-agnostic**. The same rules file works whether you're driving Claude, a coding agent, a chat UI, or a local model. The model changes; your system rules stay.
