# Context Pack: Draft Homepage Headlines — Example Local Website Project

> This is a **fictional, public-safe example** of a Context Pack. It shows how to brief an AI agent for one focused task. No real customer or private data is included. See the [Context Pack template](../templates/Context_Pack_Template.md) for a blank version, and the [sample Project Map](sample-project-map.md) it refers to.

| Field | Value |
|-------|-------|
| **Task** | Draft homepage headline options |
| **Date** | 2026-06-07 |
| **Project** | Example Local Website Project |
| **Target model(s)** | Claude / Codex / ChatGPT / local LLM — any |

## Project goal

Publish a small, fast, low-maintenance marketing website for a fictional local bakery so it can be found online and share opening hours and a contact form.

## Current state

Site structure and content are drafted. A static site generator is chosen and the homepage builds locally. Hosting is selected but not yet configured. The homepage still needs final headline copy. (Full status: [sample Project Map](sample-project-map.md).)

## Known decisions to respect

- **DR-001** — Use a static site generator (speed, low maintenance, no monthly cost).
- **DR-003** — Use a third-party form service for the contact form (no backend).
- Tone for site copy: warm, simple, local, trustworthy. Avoid hype.

## Relevant files

> The paths below are **example paths inside your own OS**, not files in this repository. For a concrete illustration of the tone note, see the [sample Knowledge note](sample-knowledge-note.md).

- `06_Projects/example-local-website/Project_Map.md` (see [sample Project Map](sample-project-map.md))
- `02_Knowledge/website-copy-tone-notes.md` — the warm/local tone guidance (see [sample Knowledge note](sample-knowledge-note.md))
- `06_Projects/example-local-website/decisions/` (the decisions above)

## Constraints

- Keep each headline under ~10 words.
- Plain, friendly language — no jargon, no marketing clichés.
- Must work for a small local bakery audience.
- Do not invent products, prices, awards, or claims about the bakery.

## Requested output

Provide **three** homepage headline options. For each:
- the headline,
- one short line on the feeling it aims for.

Return it as a short Markdown list, ready to paste into the homepage draft.

## Success criteria

- Three distinct options, all on-tone (warm, simple, local, trustworthy).
- Each within the length limit and free of invented claims.
- At least one option suitable as the primary headline without edits.

## Out of scope

- Do not rewrite other site pages.
- Do not change any decisions or the tech stack.
- Do not add taglines, subheads, or button copy unless asked.

## Action feedback target

After choosing a headline, record the outcome in
`06_Projects/example-local-website/feedback/2026-06-07-homepage-headline.md`
using the [Action Feedback template](../templates/Action_Feedback_Template.md), and update the Project Map's next actions.
