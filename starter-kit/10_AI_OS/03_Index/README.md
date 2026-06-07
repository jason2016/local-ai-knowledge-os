# 03_Index — The Map

The Index is the **table of contents** for your whole OS. It answers one question fast: *Where is everything?* Both you and your AI start here to orient before diving in.

## What belongs here

- A top-level `index.md` linking to your main areas (Knowledge, Projects, AI System)
- Curated lists: "Key knowledge notes", "Active projects", "Important decisions"
- Maps of content (MOCs) that group related notes by theme
- Pointers to your most-used templates and context packs

## What does NOT belong here

- The actual content — the Index only *points* to it. Keep notes in their home folders.
- Anything that changes minute-to-minute — link to the Project Map instead of copying its status.

## Conventions

- Keep entries short: a link plus a few words of context.
- Update the Index when you add something important, not for every small note.
- Prefer relative Markdown links so the map works in any editor and for any AI.

## Why it matters for AI

When you point an AI at your OS, the Index is the cheapest possible entry point. A good Index lets a model answer "where would I find X?" without scanning every file — and it's the natural place to send an agent first when you say *"read the index, then the relevant project."*

## Minimal starting `index.md`

```markdown
# Knowledge OS Index

## Start here
- [AI System rules](../09_AI_System/README.md)

## Active projects
- [Example Local Website Project](../06_Projects/...)

## Key knowledge
- (link your most useful notes here)

## Templates
- See ../../../templates/
```
