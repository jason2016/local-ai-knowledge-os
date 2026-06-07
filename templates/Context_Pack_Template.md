# Context Pack: <task name>

> A Context Pack is a focused bundle of just the material an AI needs for one task — instead of dumping your whole OS into a chat. Assemble it, hand it to any model, and get grounded, consistent answers. Save it near the project it serves.

| Field | Value |
|-------|-------|
| **Task** | <what we want the AI to do> |
| **Date** | YYYY-MM-DD |
| **Project** | <project name> |
| **Target model(s)** | Claude / Codex / ChatGPT / local LLM / any |

## Objective

State the task in one or two sentences. Be specific about the desired output.

> Example: "Draft three homepage headline options for the Example Local Website Project, matching a calm, professional tone."

## Read these first (in order)

1. AI System rules — `09_AI_System/system-rules.md`
2. Project Map — `06_Projects/<project>/Project_Map.md`
3. Relevant knowledge:
   - <knowledge note 1>
   - <knowledge note 2>

## Key facts

The most important constraints and details, stated plainly so the model doesn't have to infer them.

- <fact / constraint 1>
- <fact / constraint 2>

## Decisions already made

Link the Decision Records the AI must respect, with a one-line summary each.

- **DR-001** — <decision>

## Out of scope

What the AI should NOT do or change.

- <out-of-scope item>

## Expected output

Describe the exact shape of the answer you want (format, length, file to save it as).

## After the task

- Save useful output back into the project.
- Record an [Action Feedback](./Action_Feedback_Template.md) note on how it went.
- Update the Project Map.
