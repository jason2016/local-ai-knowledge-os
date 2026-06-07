# 2026-06-07 — Chapter Briefs: Build Your Local AI Knowledge OS

> **Book:** Build Your Local AI Knowledge OS
> **Recommended subtitle:** A Practical System for Giving AI Tools Reliable Project Memory
>
> **Purpose of this document:** define a writing brief for each chapter so the author and AI collaborators can later draft consistent, practical, non-hype, public-safe manuscript chapters. This is a **public planning document only** — it is not manuscript text, and the full manuscript stays private.

---

## How to use these briefs

Each chapter brief below is a contract for the chapter, not the chapter itself. When drafting, follow the brief's goal, cover the listed ideas, use only the fictional public-safe examples described, and respect the "What not to write" boundary. Keep terminology consistent with [the Method Overview](../../docs/2026-06-07-method-overview.md): **Inbox, Distill, Knowledge, Index, Projects, AI System, Context Packs, Action Feedback, Decision Records, Incident Records, Project Maps, Semantic OS Method**. Always explain a concept in plain language before using its internal name.

**Global writing rules (apply to every chapter):**
- Solve one real reader problem per chapter; state it early.
- Be practical and execution-oriented; prefer steps over theory.
- Avoid hype, guaranteed-results claims, and generic AI-productivity filler.
- Use fictional, public-safe examples only — no real customers, no invented success metrics.
- Use simple, clear English. Define terms before using them.
- Keep everything public-safe; no credentials, private records, or manuscript leakage.

---

# Part 1 — Why AI Needs a Knowledge OS

## Chapter 1 — The Context Loss Problem

### Chapter goal
Make the reader feel and name the core problem: AI tools are capable but forget project context, and that forgetting has a real, recurring cost.

### Reader pain
The reader keeps re-explaining the same background to AI tools. Every new chat starts cold. They suspect they're wasting time but haven't framed *why* it keeps happening.

### Core message
AI assistants are powerful but forgetful by design — each session starts from zero, and bigger context windows don't fix the underlying gap. The missing piece is not a smarter model; it is a stable memory outside the chat that you control.

### Key ideas to cover
- Why models start each session without prior context.
- Why larger context windows postpone but don't solve the problem.
- The hidden cost of re-explaining: time, inconsistency, and lost decisions.
- Context loss across *tools* (one model can't see another's history).
- The difference between "smarter model" and "better memory."
- A first glimpse of the solution: external, AI-readable memory.

### Practical example to include
A fictional solo maker building a small website asks an AI for help three weeks apart and has to re-paste the same goals, stack, and constraints both times — and gets slightly different advice each time because the context was phrased differently. No metrics, just the relatable friction.

### GitHub companion resources
- `docs/2026-06-07-method-overview.md` (the problem section)
- `README.md` (project rationale)

### Checklist for the reader
- [ ] List three projects where you've re-explained context to an AI.
- [ ] Note how long a typical "re-briefing" takes you.
- [ ] Identify one decision you can no longer easily find.
- [ ] Spot one place two AI tools gave inconsistent advice.
- [ ] Write one sentence describing your own context-loss pain.

### Common mistakes to avoid
- Blaming the model instead of the missing memory layer.
- Assuming a paid tier or bigger context window will fix it.
- Treating the problem as purely technical rather than organizational.

### What not to write in this chapter
- No solution walkthroughs yet (save structure for Part 2).
- No vendor comparisons or model benchmarks.
- No fear-mongering about AI; keep it grounded and practical.

---

## Chapter 2 — Why Chat History Is Not Business Memory

### Chapter goal
Show why relying on chat history as a record of decisions and knowledge fails, and why a deliberate memory system is needed instead.

### Reader pain
The reader treats their AI chat history as a kind of archive, then can't find what they need, loses it to a vendor change, or realizes it was never organized to begin with.

### Core message
Chat history is a transcript, not a memory. It is hard to search, easy to lose, locked to one vendor, and structured for conversation rather than reuse. A reliable business memory must be external, organized by meaning, and readable by any tool.

### Key ideas to cover
- Transcript vs. structured memory: what each is good for.
- Why search inside chat tools is unreliable for real retrieval.
- Vendor lock-in and the fragility of cloud-only history.
- Conversations bury decisions instead of surfacing them.
- The risk of treating private chat logs as a system of record.
- What a trustworthy memory needs: ownership, structure, portability.

### Practical example to include
A fictional indie hacker tries to recall why they chose a static site over a CMS, scrolls through weeks of chats, and can't reconstruct the reasoning — illustrating that the decision was never recorded as a decision.

### GitHub companion resources
- `docs/2026-06-07-method-overview.md`
- `templates/Decision_Record_Template.md` (preview of the fix)

### Checklist for the reader
- [ ] Try to find one specific past decision in your chat history; time it.
- [ ] List tools whose history you can't easily export.
- [ ] Identify one piece of knowledge trapped only in a chat.
- [ ] Decide what "system of record" should mean for your work.
- [ ] Note one thing you'd lose if a tool shut down tomorrow.

### Common mistakes to avoid
- Confusing "I can scroll back" with "I have a memory system."
- Storing sensitive business records only inside a chat tool.
- Assuming export equals organization.

### What not to write in this chapter
- No criticism of specific named products' business practices.
- No privacy scare tactics; state risks plainly and move on.
- No full template walkthroughs yet (that's Part 3).

---

## Chapter 3 — From Notes to AI-Readable Systems

### Chapter goal
Bridge from ordinary note-taking to a system structured for AI, introducing the idea of organizing by role and meaning.

### Reader pain
The reader has notes — maybe a whole Obsidian vault — but AI tools still can't reliably use them. The notes are built for human browsing, not for an agent to act on.

### Core message
Normal notes optimize for a human reading them; AI agents need to know *what each item is* and *where to start*. Organizing knowledge by role and meaning — the idea behind the Semantic OS Method — turns a pile of notes into a system an AI can navigate.

### Key ideas to cover
- Why "folders by topic" don't help an AI act.
- The concept of *role*: input, distilled meaning, durable knowledge, decision, project state, system rules.
- Introduce the Semantic OS Method in plain terms (meaning and role over app and topic).
- Why plain Markdown is the right substrate (portable, readable, diffable).
- How structure lets you point an AI at exactly the right material.
- The shift from "notes I read" to "memory an AI uses."

### Practical example to include
A fictional technical writer has a tidy vault, but when they ask an AI to "use my notes," it can't tell background reading from final decisions. Adding clear roles (a Knowledge note vs. a Decision Record) makes the same material usable.

### GitHub companion resources
- `docs/2026-06-07-method-overview.md` (Semantic OS Method section)
- `starter-kit/` (preview of role-based folders)

### Checklist for the reader
- [ ] Pick five notes and label each with its role.
- [ ] Find one note mixing raw input and conclusions; split it mentally.
- [ ] Identify where decisions currently live in your notes.
- [ ] Confirm your notes are in plain Markdown (or could be).
- [ ] Write a one-line definition of "role" in your own words.

### Common mistakes to avoid
- Reorganizing by topic again instead of by role.
- Over-tagging instead of clarifying what each item *is*.
- Treating the method as an app feature rather than a way of organizing.

### What not to write in this chapter
- No full folder-structure walkthrough yet (that's Chapter 5).
- No tool-specific Obsidian plugin tutorials.
- No abstract knowledge-management theory beyond what's needed to act.

---

# Part 2 — The Local AI Knowledge OS Structure

## Chapter 4 — The Local-First Principle

### Chapter goal
Make the case for keeping the source of truth local and in plain Markdown, and show what that buys the reader.

### Reader pain
The reader's knowledge is scattered across cloud apps they don't control, can't fully export, and can't use offline or with local models.

### Core message
A reliable memory must be one you own. Keeping the source of truth in local Markdown makes it portable, private, offline-capable, version-controllable, and readable by any model — including local LLMs — without a special integration.

### Key ideas to cover
- What "local-first" means and what it does not (sync is fine; lock-in is not).
- Benefits: ownership, portability, offline use, backups, version control.
- Why plain Markdown beats proprietary formats for longevity.
- How local-first enables fully private workflows with local LLMs.
- Where syncing/backup fit without giving up control.
- The boundary between public-safe content and private content (per repo rules).

### Practical example to include
A fictional small business owner keeps their knowledge OS in a synced folder and a private backup, then uses a local LLM offline to draft an internal note — showing privacy and control without cloud dependence.

### GitHub companion resources
- `docs/2026-06-07-method-overview.md`
- `CLAUDE.md` (public vs. private boundaries, as a model for the reader's own rules)

### Checklist for the reader
- [ ] Choose where your local source of truth will live.
- [ ] Decide your backup method (and test a restore).
- [ ] Confirm everything important is plain Markdown.
- [ ] Define what stays private vs. shareable.
- [ ] Verify you can open your notes with no proprietary app.

### Common mistakes to avoid
- Equating "local-first" with "never sync" — sync is allowed.
- Putting secrets or credentials into AI-readable files.
- Choosing a proprietary format that traps your content.

### What not to write in this chapter
- No deep DevOps/Git tutorials; mention version control lightly.
- No security-hardening deep dive (privacy basics belong here, not a full guide).
- No claims that local-first is the only valid choice for everyone.

---

## Chapter 5 — The Core Folder Structure

### Chapter goal
Walk the reader through the actual OS layout so they can copy it and start using it the same day.

### Reader pain
The reader is convinced they need structure but doesn't know what folders to create or what belongs where.

### Core message
A small, role-based folder structure — Inbox, Distill, Knowledge, Index, Projects, and an AI System area — gives every piece of content a clear home and a clear job, so both the reader and an AI always know where to look.

### Key ideas to cover
- Each folder's single job: Inbox (capture), Distill (process), Knowledge (keep), Index (map), Projects (active work), AI System (rules for agents).
- Why the numbered prefixes keep order stable and leave room to grow.
- What belongs in each folder and what does not.
- The flow: Capture → Distill → Keep → Index → Project work → Feed AI → Feedback.
- How to copy the starter kit into an existing vault.
- How the structure stays the same as the number of projects grows.

### Practical example to include
A walkthrough of setting up the structure for a fictional "Example Local Website Project," showing one item moving from Inbox to Distill to a Knowledge note, and the project getting its own folder under Projects.

### GitHub companion resources
- `starter-kit/README.md` and the folder READMEs under `starter-kit/10_AI_OS/`
- `examples/sample-project-map.md`

### Checklist for the reader
- [ ] Copy the starter-kit structure into your vault.
- [ ] Confirm each folder has its README/role clear in your mind.
- [ ] Move one real item through Inbox → Distill → Knowledge.
- [ ] Create your first project folder under Projects.
- [ ] Add a minimal `index.md` linking your main areas.

### Common mistakes to avoid
- Renaming folders by topic and losing the role-based logic.
- Skipping the AI System folder because it "isn't needed yet."
- Over-engineering the structure before there's content to hold.

### What not to write in this chapter
- No deep dive into Project Maps/Decisions yet (that's Chapter 6).
- No exhaustive list of optional folders; keep to the core six.
- No app-specific setup that breaks tool-agnosticism.

---

## Chapter 6 — Project Maps, Decisions, and Incidents

### Chapter goal
Introduce the three records that hold project state and reasoning: the Project Map, the Decision Record, and the Incident Record.

### Reader pain
The reader's project status, the reasons behind choices, and the lessons from things going wrong all live in their head or in scattered chats — and disappear over time.

### Core message
A project needs a living front door and a memory of *why*. The Project Map tracks current state; Decision Records capture why choices were made; Incident Records capture what went wrong and how to prevent it. Together they make a project legible to future-you and to any AI.

### Key ideas to cover
- The Project Map as the front door: goal, status, decisions, open questions, next actions, reusable knowledge.
- Decision Records: capturing context, options, decision, and rationale.
- Incident Records: timeline, root cause, resolution, prevention.
- Why recording *why* prevents relitigating settled choices.
- How these records feed an AI working on the project.
- Keeping records short and current rather than perfect.

### Practical example to include
For the fictional Example Local Website Project: a Project Map summary, one Decision Record ("use a static site generator, for speed and low maintenance"), and one Incident Record ("a deploy showed a blank page; root cause was a misconfigured publish path"). No metrics, just realistic detail.

### GitHub companion resources
- `templates/Project_Map_Template.md`, `templates/Decision_Record_Template.md`, `templates/Incident_Record_Template.md`
- `examples/sample-project-map.md`

### Checklist for the reader
- [ ] Create a Project Map for one active project.
- [ ] Write one Decision Record for a choice you've already made.
- [ ] Capture one past incident as an Incident Record.
- [ ] List your project's current open questions.
- [ ] Add three concrete next actions to the map.

### Common mistakes to avoid
- Letting the Project Map go stale (it must reflect current state).
- Writing decisions without the rationale (the *why* is the point).
- Turning incident records into blame instead of learning.

### What not to write in this chapter
- No Action Feedback or Context Pack detail yet (Part 3).
- No real incidents involving real people or organizations.
- No rigid bureaucracy that discourages quick, honest records.

---

# Part 3 — Templates and Workflows

## Chapter 7 — Building Reusable Templates

### Chapter goal
Teach the reader to use and adapt the core templates so capturing structured records becomes fast and consistent.

### Reader pain
The reader knows records are useful but writing them from scratch each time is slow, so they skip it — and the system decays.

### Core message
Templates remove the friction that kills good habits. A small set of consistent, copy-ready templates makes it fast to record decisions, incidents, project state, feedback, and context — and consistency is what makes the records reusable by an AI.

### Key ideas to cover
- Why templates lower the activation energy for good records.
- The core set: Project Map, Decision Record, Incident Record, Action Feedback, Context Pack.
- Anatomy of a good template: clear sections, generic placeholders, no private examples.
- Adapting templates to your work without breaking consistency.
- Consistent naming and dated filenames for retrieval.
- How consistent structure helps AI parse and reuse records.

### Practical example to include
Show a blank template being filled in for the fictional Example Local Website Project — e.g. a Decision Record going from placeholders to a realistic, public-safe entry.

### GitHub companion resources
- All of `templates/`
- `examples/sample-project-map.md`

### Checklist for the reader
- [ ] Copy the five core templates into your OS.
- [ ] Fill one template end-to-end for a real project.
- [ ] Adjust one template's sections to fit your work.
- [ ] Set a filename convention (e.g. `YYYY-MM-DD-title.md`).
- [ ] Confirm placeholders contain no private data.

### Common mistakes to avoid
- Over-customizing until templates lose consistency.
- Adding so many fields that no one fills them in.
- Copying private examples into shared templates.

### What not to write in this chapter
- No feedback-loop theory yet (that's Chapter 8).
- No tool-specific template plugins.
- No bloated "enterprise" template variants.

---

## Chapter 8 — Action Feedback and Learning Loops

### Chapter goal
Teach the reader to close the loop by recording what actually happened after acting, so the system improves over time.

### Reader pain
The reader makes plans and acts on AI suggestions, but never captures the outcome — so the same lessons get relearned and the system grows without getting smarter.

### Core message
A knowledge system that only stores plans gets bigger, not better. Recording what actually happened — expected vs. actual, what worked, what didn't, the lesson — turns experience into reusable knowledge and creates a genuine learning loop.

### Key ideas to cover
- The difference between storing plans and storing outcomes.
- The Action Feedback record: expected result, actual result, what worked, what didn't, lesson, next action.
- How feedback promotes durable lessons into Knowledge.
- Why honest "what didn't work" entries are the most valuable.
- Building a lightweight rhythm for capturing feedback.
- How feedback feeds back into the Project Map's next actions.

### Practical example to include
For the fictional Example Local Website Project: an Action Feedback note after publishing the homepage — expected a clean deploy, hit the blank-page issue, fixed the publish path, lesson recorded as reusable knowledge. No metrics, just the loop.

### GitHub companion resources
- `templates/Action_Feedback_Template.md`
- `examples/sample-project-map.md` (reusable knowledge section)

### Checklist for the reader
- [ ] Write one Action Feedback note for a recent action.
- [ ] Compare what you expected vs. what happened.
- [ ] Extract one reusable lesson and move it to Knowledge.
- [ ] Update the Project Map's next actions from the outcome.
- [ ] Set a regular time to record feedback.

### Common mistakes to avoid
- Only recording successes; the failures teach more.
- Writing feedback so long it never gets written.
- Letting lessons sit in feedback notes instead of promoting them.

### What not to write in this chapter
- No fabricated metrics or success rates.
- No Context Pack mechanics yet (Chapter 9).
- No motivational filler about "continuous improvement."

---

## Chapter 9 — Context Packs for AI Agents

### Chapter goal
Teach the reader to assemble focused Context Packs so AI gets exactly what it needs for one task.

### Reader pain
The reader either dumps everything into a chat (and gets unfocused or truncated answers) or pastes too little (and gets generic ones). They lack a repeatable way to brief an AI.

### Core message
Don't hand an AI your whole system — hand it a Context Pack: a small, curated bundle of just the rules, project state, and knowledge relevant to one task. Focused context produces grounded, consistent answers and respects context limits.

### Key ideas to cover
- Why "dump everything" and "paste too little" both fail.
- The Context Pack: objective, what to read first, key facts, decisions to respect, out-of-scope, expected output.
- Curating a pack from existing OS files (mostly Knowledge + Project Map + AI System rules).
- Reusing and updating packs across similar tasks.
- How packs keep answers consistent across different models.
- Saving output back and recording feedback after the task.

### Practical example to include
A Context Pack for the fictional Example Local Website Project: "Draft three homepage headline options in a calm, local tone," pointing to the Project Map and one Knowledge note, with clear out-of-scope items.

### GitHub companion resources
- `templates/Context_Pack_Template.md`
- `starter-kit/10_AI_OS/09_AI_System/` (rules referenced by packs)

### Checklist for the reader
- [ ] Pick one upcoming task to brief an AI on.
- [ ] Build a Context Pack listing only the relevant files.
- [ ] State the objective and the out-of-scope items.
- [ ] Run the task with the pack and compare to an unbriefed run.
- [ ] Save the output and record an Action Feedback note.

### Common mistakes to avoid
- Stuffing the pack with everything "just in case."
- Omitting the decisions the AI must respect.
- Forgetting to define the expected output format.

### What not to write in this chapter
- No model-specific API instructions (that's Part 4 context).
- No claims that packs guarantee perfect output.
- No exposure of private files inside example packs.

---

# Part 4 — Working with AI Agents

## Chapter 10 — Using Claude, Codex, ChatGPT, and Local LLMs

### Chapter goal
Show how the same OS feeds different AI tools, keeping the system tool-agnostic.

### Reader pain
The reader uses several AI tools, none of which share memory, and doesn't know how to use one knowledge source across all of them.

### Core message
Because the OS is plain Markdown with clear roles, every tool can work from the same material — you just deliver it through each tool's interface. The pattern is identical across tools: assemble a Context Pack, let the AI read the rules plus project state plus knowledge, act, then record feedback.

### Key ideas to cover
- The shared pattern: pack → read rules + Project Map + Knowledge → act → feedback.
- Claude / coding agents: pointing them at files or packs as project memory.
- Chat UIs (e.g. ChatGPT): pasting a Context Pack for the same grounding.
- Local LLMs (e.g. Ollama, LM Studio): reading local files for fully private, offline work.
- Why "the model changes, the OS stays" keeps you future-proof.
- Choosing the right tool for a task without fragmenting your memory.

### Practical example to include
The same Context Pack from Chapter 9 used in two different tools, producing comparably grounded results — illustrating tool-agnosticism without naming benchmarks or metrics.

### GitHub companion resources
- `docs/2026-06-07-method-overview.md` (the "how each tool uses it" section)
- `templates/Context_Pack_Template.md`

### Checklist for the reader
- [ ] List the AI tools you currently use.
- [ ] Run one Context Pack through two of them.
- [ ] Confirm each tool can reach your knowledge (paste or file access).
- [ ] Note which tool you prefer for which kind of task.
- [ ] Verify a local LLM can read your files if privacy matters.

### Common mistakes to avoid
- Building tool-specific structures that break portability.
- Letting each tool grow its own private memory again.
- Assuming one tool is "best" for everything.

### What not to write in this chapter
- No step-by-step product UI tutorials that will date quickly.
- No benchmark claims or model rankings.
- No vendor favoritism; keep it neutral and practical.

---

## Chapter 11 — Writing AI Collaboration Rules

### Chapter goal
Teach the reader to write the AI System rules and guardrails that make any model behave consistently inside the OS.

### Reader pain
The reader gets inconsistent AI behavior — it invents facts, ignores past decisions, or saves output in the wrong place — because nothing tells the AI how to work.

### Core message
An AI works better when it has rules. A small AI System area — how to navigate the OS, what reading order to follow, and hard guardrails — turns an unpredictable assistant into a reliable collaborator that respects your structure and your decisions.

### Key ideas to cover
- What belongs in the AI System area: system rules, reading order, reusable prompts, guardrails.
- A default reading order (Index → Project Map → relevant Knowledge → act).
- Guardrails: never invent decisions, never overwrite records, never expose secrets.
- Output conventions: where new records go, naming, link style.
- Why the same rules work across all models (tool-agnostic).
- Keeping rules short enough that they're actually followed.

### Practical example to include
A short, fictional `system-rules.md` for a personal OS — a handful of navigation rules and three hard guardrails — shown as a public-safe example the reader can adapt. (Mirror the structure shown in the AI System folder README, not any private rules.)

### GitHub companion resources
- `starter-kit/10_AI_OS/09_AI_System/README.md`
- `CLAUDE.md` (as a public-safe model of guardrails in practice)

### Checklist for the reader
- [ ] Write a short system-rules file for your OS.
- [ ] Define a default reading order for agents.
- [ ] List three hard guardrails the AI must never break.
- [ ] State where new records should be saved.
- [ ] Test the rules by giving an AI a small task.

### Common mistakes to avoid
- Writing rules so long no model reliably follows them.
- Omitting guardrails about secrets and overwriting.
- Embedding tool-specific quirks that break portability.

### What not to write in this chapter
- No private or proprietary rule sets.
- No prompt-engineering "tricks" framed as guarantees.
- No security deep dive beyond practical guardrails.

---

## Chapter 12 — Avoiding AI Drift and Context Pollution

### Chapter goal
Help the reader keep AI output accurate over time by preventing drift, stale context, and polluted inputs.

### Reader pain
The reader's AI gradually gives worse or contradictory answers as old, wrong, or excessive context creeps into the system and into prompts.

### Core message
AI reliability degrades when context is stale, contradictory, or bloated. Keeping records current, retiring outdated knowledge, and giving the AI focused, clean Context Packs prevents drift and keeps answers trustworthy.

### Key ideas to cover
- What "drift" and "context pollution" mean in plain terms.
- How stale Project Maps and outdated decisions mislead an AI.
- Why bigger context is not better context.
- Curating and pruning Knowledge so it stays trustworthy.
- Marking superseded decisions instead of deleting history silently.
- A maintenance rhythm to keep the OS clean.

### Practical example to include
The fictional Example Local Website Project where an old decision (a CMS) was later superseded (static site); showing how marking the old Decision Record as "superseded" prevents an AI from acting on outdated context.

### GitHub companion resources
- `templates/Decision_Record_Template.md` (status: superseded)
- `examples/sample-project-map.md`

### Checklist for the reader
- [ ] Review one Project Map and update its status.
- [ ] Mark any superseded decisions clearly.
- [ ] Prune one outdated or duplicate Knowledge note.
- [ ] Trim one Context Pack down to only what's relevant.
- [ ] Schedule a recurring cleanup rhythm.

### Common mistakes to avoid
- Hoarding context "just in case" until it pollutes results.
- Deleting decision history instead of marking it superseded.
- Letting Project Maps drift out of date.

### What not to write in this chapter
- No alarmist claims about AI "hallucination" as inevitable doom.
- No promises that maintenance eliminates all errors.
- No complex tooling requirements; keep maintenance simple.

---

# Part 5 — Turning the System into a Product or Service

## Chapter 13 — Packaging the System for Yourself

### Chapter goal
Help the reader turn their OS into a sustainable personal practice with habits, maintenance, and reuse.

### Reader pain
The reader set up a system but worries it will decay, become a chore, or get cluttered as projects pile up.

### Core message
A knowledge OS only pays off if it's maintained lightly and consistently. Simple daily and weekly habits, regular harvesting of reusable knowledge, and clean archiving keep the system lean and valuable over the long term.

### Key ideas to cover
- Daily and weekly rhythms (process Inbox, update Project Maps, record feedback).
- Harvesting reusable lessons from finished projects into Knowledge.
- Archiving completed projects without losing their lessons.
- Keeping the system lean: prune, link, and consolidate.
- Personal reuse: starting new projects from past patterns.
- Backups and the public/private boundary as ongoing habits.

### Practical example to include
A fictional indie hacker's lightweight weekly routine: clear the Inbox, update two Project Maps, harvest one lesson into Knowledge, archive one finished project. Realistic and small.

### GitHub companion resources
- `starter-kit/` (the structure being maintained)
- `templates/Action_Feedback_Template.md`

### Checklist for the reader
- [ ] Define your weekly maintenance routine.
- [ ] Process your Inbox to near-empty once this week.
- [ ] Harvest one lesson from a finished project.
- [ ] Archive one completed project folder.
- [ ] Confirm backups are running.

### Common mistakes to avoid
- Building elaborate routines you won't keep.
- Never archiving, so active projects get buried.
- Hoarding finished projects without extracting lessons.

### What not to write in this chapter
- No productivity-guru lifestyle claims.
- No rigid systems that demand hours of upkeep.
- No tool-specific automation that breaks portability.

---

## Chapter 14 — Packaging the System for Clients

### Chapter goal
Show consultants and freelancers how to offer the system as a repeatable service — public-safe, with strict privacy boundaries and no income promises.

### Reader pain
The reader wants to deliver this method to clients but doesn't know how to standardize it or how to keep client data safe and separated.

### Core message
The same method that organizes your work can be delivered as a service. Standardize with templates and starter kits, keep every client's data private and isolated, and separate the public method from private client specifics. This chapter is about *how to package*, not promises of earnings.

### Key ideas to cover
- Turning the method into a repeatable delivery (intake → setup → handover).
- Using the starter kit and templates as the reusable basis per client.
- Strict separation: each client's data stays private and isolated.
- Keeping the public method distinct from private client implementations.
- Handover and training so clients can maintain it themselves.
- Ethics and honesty: set expectations, avoid guaranteed-results claims.

### Practical example to include
A fictional, generic engagement outline for "a small business" (no real client): standard folders set up, four core templates installed, a short handover checklist. No names, no metrics, no revenue figures.

### GitHub companion resources
- `starter-kit/` and `templates/` (the reusable delivery basis)
- `CLAUDE.md` (public/private boundary as a model for client work)

### Checklist for the reader
- [ ] Draft a standard setup checklist you could reuse per engagement.
- [ ] Decide how you'll isolate each client's private data.
- [ ] Define what stays public method vs. private specifics.
- [ ] Prepare a simple client handover/training outline.
- [ ] Write an honest scope statement (no guaranteed outcomes).

### Common mistakes to avoid
- Mixing client data into shared or public materials.
- Promising specific business results or savings.
- Reinventing the setup for every client instead of standardizing.

### What not to write in this chapter
- No real client names, data, or case details.
- No income, ROI, or "guaranteed results" claims.
- No private contracts, pricing secrets, or proprietary playbooks.

---

## Chapter 15 — The Future of Local AI Knowledge Systems

### Chapter goal
Leave the reader with a durable, forward-looking perspective and a clear sense of how to keep the system relevant as AI evolves.

### Reader pain
The reader worries their setup will be obsolete as models and tools change rapidly.

### Core message
Models will keep changing; an owned, structured, plain-text memory is what stays useful across them. A local AI knowledge system is a durable foundation precisely because it isn't tied to any one tool — and it grows more valuable as AI agents become more capable.

### Key ideas to cover
- Why local, structured memory outlasts any single model or app.
- How more capable agents make a well-structured OS *more* valuable, not less.
- Trends to watch, described cautiously (no hype, no predictions-as-facts).
- Extending the Semantic OS Method to new kinds of work.
- Scaling from solo to small team while keeping the principles.
- Keeping ownership, privacy, and portability as guiding values.

### Practical example to include
A brief, realistic sketch of a fictional small team adopting the same structure a solo user built — same folders and templates, now shared — showing the method scales without changing its core.

### GitHub companion resources
- `docs/2026-06-07-method-overview.md`
- `book/outline/` (where the method's public planning continues)

### Checklist for the reader
- [ ] Note which parts of your OS are tool-independent (most should be).
- [ ] Identify one way you'd extend the method to new work.
- [ ] Decide what would change if a teammate joined.
- [ ] Reaffirm your ownership, privacy, and backup choices.
- [ ] Plan your next improvement to the system.

### Common mistakes to avoid
- Chasing every new tool and fragmenting your memory.
- Treating predictions as certainties.
- Abandoning the principles when scaling to a team.

### What not to write in this chapter
- No speculative AGI or hype-driven predictions.
- No claims about specific future products or release dates.
- No abandonment of the public-safe, no-overpromise rules.

---

## Cross-chapter consistency notes

- Reuse the single fictional running example — the **Example Local Website Project** — across chapters so readers follow one thread. See [`examples/sample-project-map.md`](../../examples/sample-project-map.md).
- Keep term names identical to the [Method Overview](../../docs/2026-06-07-method-overview.md) and the [starter kit](../../starter-kit/README.md).
- Every chapter should point to at least one repo companion resource so readers can act immediately.
- Honor the repository rules in [`CLAUDE.md`](../../CLAUDE.md): public-safe only, no private data, no manuscript text, no overpromising.
