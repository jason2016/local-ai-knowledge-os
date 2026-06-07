# Folder Structure Diagram

The Local AI Knowledge OS is a small, role-based folder structure. Each folder has one job, so both you and your AI tools always know where to look. This is the layout you copy from [`starter-kit/10_AI_OS/`](../../starter-kit/10_AI_OS/).

```mermaid
flowchart TD
    ROOT["10_AI_OS/"] --> I["00_INBOX — Raw capture"]
    ROOT --> D["01_Distill — Process into meaning"]
    ROOT --> K["02_Knowledge — Durable reusable notes"]
    ROOT --> X["03_Index — Map of the system"]
    ROOT --> P["06_Projects — Active project memory"]
    ROOT --> S["09_AI_System — Rules for AI tools"]

    classDef root fill:#F7F4EE,stroke:#1F4E79,color:#202124
    classDef folder fill:#F7F4EE,stroke:#C9C3B8,color:#202124
    classDef knowledge fill:#F7F4EE,stroke:#4F7D5A,color:#202124
    classDef system fill:#F7F4EE,stroke:#C99735,color:#202124

    class ROOT root
    class I,D,X,P folder
    class K knowledge
    class S system
```

Plain-text view:

```text
10_AI_OS/
├── 00_INBOX/      Raw capture — everything lands here first
├── 01_Distill/    Process into meaning
├── 02_Knowledge/  Durable, reusable notes
├── 03_Index/      Map of the system
├── 06_Projects/   Active project memory
└── 09_AI_System/  Rules for AI tools
```

## Why this structure matters

- **Role over topic.** Each folder defines what a file *is* (raw input, distilled meaning, durable knowledge, a map, project state, or AI rules) — not just what it's about. This is what lets an AI navigate it reliably.
- **One job per folder.** Capture, processing, and keeping stay separate, so nothing gets lost between "I wrote it down" and "I can reuse it."
- **Stable, predictable order.** The numbered prefixes keep the layout consistent and leave room to grow (`04_`, `05_`, `07_`, `08_`) without reshuffling.
- **A clear front and back door.** `03_Index` is where you (and an agent) start to orient; `09_AI_System` is where the rules for AI tools live, keeping the OS tool-agnostic.
- **Lightweight and copyable.** It's just folders of Markdown — no app, no database. Copy it once and start using it the same day.

See each folder's README under [`starter-kit/10_AI_OS/`](../../starter-kit/10_AI_OS/) for what belongs where.
