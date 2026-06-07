# Project Map: Example Local Website Project

> This is a **fictional, illustrative example** showing how a Project Map records the state of real work. No real customer or private data is included. Use it as a model for your own maps. See the [Project Map template](../templates/Project_Map_Template.md) for a blank version.

| Field | Value |
|-------|-------|
| **Project** | Example Local Website Project |
| **Owner** | Maker (solo) |
| **Started** | 2026-05-20 |
| **Last updated** | 2026-06-07 |
| **Status** | Active |

## Goal

Publish a small, fast, low-maintenance marketing website for a fictional local bakery so it can be found online and share opening hours and a contact form. "Done" means the site is live, mobile-friendly, and updatable in under five minutes without a developer.

## Current status

The site structure and content are drafted. A static site generator has been chosen and the homepage builds locally. Hosting is selected but not yet configured. We had one deploy incident (blank page) which is now resolved. Next focus: configure hosting and ship the first public version.

## Key decisions

- **DR-001** — Use a static site generator instead of a CMS, for speed and zero monthly cost. → `decisions/2026-05-22-choose-static-site-generator.md`
- **DR-002** — Host on a free static host with automatic builds from the repo. → `decisions/2026-05-28-choose-static-host.md`
- **DR-003** — Use a third-party form service for the contact form to avoid running a backend. → `decisions/2026-06-02-contact-form-approach.md`

## Open questions

- [ ] Do we need a custom domain for launch, or is the host subdomain enough for v1?
- [ ] Should opening hours live in a single data file so they're easy to update?
- [ ] Is a cookie/consent banner required for the contact form provider?

## Next actions

- [ ] Configure the static host and connect the repository.
- [ ] Move opening hours into one `hours.yml` data file.
- [ ] Run a mobile layout check on the homepage and contact page.
- [ ] Publish v1 and record an Action Feedback note.

## Reusable knowledge

- A misconfigured build output path can publish an empty folder → always verify the publish directory after the first deploy. (From INC-001; promote to `02_Knowledge/`.)
- Static site + third-party form service = no backend to maintain for small sites. → candidate Knowledge note.

## Context for AI

- Tone for site copy: warm, simple, local, trustworthy. Avoid hype.
- Keep the build fast and dependencies minimal.
- Do not introduce a database or server — this is intentionally static.
- Read order: this Project Map → relevant Decision Records → then propose changes.

## Related

- Decision Records: `decisions/`
- Incident: `2026-06-01-deploy-blank-page.md` (INC-001, resolved)
- Feedback log: `feedback/`
- Context Packs: `context-packs/`
