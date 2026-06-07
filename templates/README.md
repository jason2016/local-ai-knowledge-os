# Templates

Reusable, copy-ready Markdown templates for project memory. Each one captures a specific kind of knowledge so both you and your AI tools can find and reuse it later.

All templates are public-safe and use generic placeholders only — no private data. See the [method overview](../docs/2026-06-07-method-overview.md) for how they fit together.

## Which template should I use?

| You want to... | Use this | Template |
|----------------|----------|----------|
| Track a project's goal, status, and next actions | **Project Map** | [Project_Map_Template.md](Project_Map_Template.md) |
| Record *why* you chose something | **Decision Record** | [Decision_Record_Template.md](Decision_Record_Template.md) |
| Learn from something that went wrong | **Incident Record** | [Incident_Record_Template.md](Incident_Record_Template.md) |
| Brief an AI for one specific task | **Context Pack** | [Context_Pack_Template.md](Context_Pack_Template.md) |
| Capture what actually happened after acting | **Action Feedback** | [Action_Feedback_Template.md](Action_Feedback_Template.md) |

### When to use each

- **Project Map** — the living front door to a project. Start one for every project. It holds goal, status, key decisions, open questions, next actions, and reusable knowledge. Update it often; it's the first thing you (and your AI) read.

- **Decision Record** — use the moment you make a meaningful choice (a tool, an approach, a trade-off). It captures the context, the options, the decision, and the rationale so the *why* isn't lost and isn't relitigated later.

- **Incident Record** — use after something breaks or goes wrong. It captures a short timeline, the root cause, the fix, and how to prevent a repeat. The goal is learning, not blame.

- **Context Pack** — use right before you ask an AI to do a task. Instead of dumping your whole system into a chat, you assemble a focused bundle: the objective, what to read first, key facts, decisions to respect, what's out of scope, and the expected output. Focused context = grounded answers.

- **Action Feedback** — use right after you act on a plan or an AI suggestion. It records expected vs. actual result, what worked, what didn't, the reusable lesson, and the next action. This is the step that makes the system get smarter over time.

## Suggested order for first-time users

If you're just starting, use the templates in this order:

1. **Project Map** — set up one project so you have a front door.
2. **Decision Record** — capture one decision you've already made (good warm-up).
3. **Context Pack** — brief an AI on one small task from that project.
4. **Action Feedback** — record how the task went.
5. **Incident Record** — add this when (and only when) something actually goes wrong.

See the full cycle in action: [examples/sample-memory-loop.md](../examples/sample-memory-loop.md).

## How to use a template

1. Copy the template file into your own OS (e.g. into `06_Projects/your-project/`).
2. Rename it with a clear, dated filename: `2026-06-07-short-title.md`.
3. Fill in the placeholders. Keep entries short and current rather than perfect.
4. Link related records to each other so your AI can follow the connections.

> Keep it public-safe: never put credentials, customer data, or private records into files an AI will read.
