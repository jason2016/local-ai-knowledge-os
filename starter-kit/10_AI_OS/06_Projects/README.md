# 06_Projects — Active Work

Projects is where the OS meets real work. Each active project gets its own folder containing a **Project Map** — a living document that tracks goal, status, decisions, open questions, next actions, and reusable knowledge.

This is the folder your AI will read most often, because it holds **current state**.

## What belongs here

- One subfolder per project
- A `Project_Map.md` in each (see the [Project Map template](../../../templates/Project_Map_Template.md))
- Project-specific Decision Records and Incident Records
- Context Packs assembled for that project's tasks
- Working files and drafts tied to the project

## What does NOT belong here

- General, reusable knowledge → promote it to [`02_Knowledge/`](../02_Knowledge/README.md)
- Unsorted captures → [`00_INBOX/`](../00_INBOX/README.md)
- Global AI rules → [`09_AI_System/`](../09_AI_System/README.md)

## Suggested layout

```
06_Projects/
├── example-local-website/
│   ├── Project_Map.md
│   ├── decisions/
│   ├── context-packs/
│   └── feedback/
└── another-project/
    └── Project_Map.md
```

## Conventions

- The **Project Map is the front door** to each project. Keep it current.
- Record decisions as they happen using the [Decision Record template](../../../templates/Decision_Record_Template.md).
- When a project ends, harvest its reusable lessons into `02_Knowledge/`, then archive the folder.

## Why it matters for AI

The Project Map gives an AI the *state of play* in one file: what we're trying to do, what's been decided, what's open, and what's next. Hand it the Project Map plus a Context Pack and the model can act with full awareness instead of guessing. See [`examples/sample-project-map.md`](../../../examples/sample-project-map.md) for a complete example.
