# Instructions for PersonalWebsite

## Project

Personal website for Beksultan Baimagambetov, supporting his YC founder profile as NovaLab's CTO and co-founder and showing actual engineering work. The chosen visual direction is Engineering Notebook.

Read DESIGN.md and CONTENT.md before implementation. DESIGN.md owns visual and interaction direction. CONTENT.md owns factual copy, evidence status, and missing assets. Current direct user instructions take priority; update the documents when an agreed decision changes.

## Current stage

This repository starts with planning documents only. The current task is to update those documents for the NovaLab application. Begin product implementation when the user gives the implementation task; do not scaffold an application just because these instructions exist.

The first requested implementation should be one homepage draft with a polished hero and one complete project entry, followed by screenshot review. The longer homepage structure is in DESIGN.md.

## Factual integrity

- NovaLab is the current YC startup and lead case study. AI Builders is outside the default homepage scope.
- NovaLab has an MVP according to the owner. Its first free school pilot is planned for 3 November 2026: one school, one grade-7 class, and one physics teacher. Do not claim it launched or produced results without a later update.
- Improved learning outcomes are a hypothesis. Do not imply proven educational effectiveness, paid adoption, or measured growth.
- Distinguish the historical React/Three.js prototype from the current platform and Unity WebGL laboratories. Confirm Beksultan's exact current contributions before writing detailed first-person ownership claims.
- Recheck date-sensitive pilot wording before publication; do not automatically advance status when the scheduled date passes.
- Keep private repository links and private source details out of this public repository. Use owner-supplied publishable facts and approved assets.
- Use OWNER/CV facts for draft copy while preserving qualifications. Repository existence does not verify implementation or authorship.
- Do not invent results, timelines, architecture, testimonials, clients, tests, metrics, product screenshots, or links.
- Distinguish Beksultan's work from team outcomes.
- Evidence labels and PENDING notes are editorial metadata, not UI copy.
- Omit missing assets or actions cleanly. Ask only when missing input blocks the next meaningful step.
- Keep private background material, credentials, raw personal-file inventories, and internal company information out of this public repository.

## Scope and implementation

- Preserve the Engineering Notebook direction; do not restart aesthetic discovery unless asked.
- Favor static content and minimal client JavaScript. Preserve the existing stack if one is later added; otherwise propose a lightweight Vercel-compatible choice in the implementation response.
- No authentication, database, CMS, analytics, or contact backend is needed for the first draft. NovaLab's architecture describes the featured product, not this website's required implementation.
- Use semantic HTML, accessible contrast and focus, responsive layouts, and reduced-motion support.
- No scroll hijacking, fake terminal, decorative code dumps, skill percentage bars, or generic card grid for every section.
- Use real content and purposeful diagrams. Do not use generated imagery to imply a real person, product, or achievement.
- Separate structured project content from reusable presentation components where this simplifies maintenance.
- Respect existing work and inspect git status before changes. Never reset or overwrite unrelated changes.
- Work within this repository. Do not scan home directories, WSL, or Windows user folders unless the user explicitly requests that separate task.

## Validation and delivery

- For documentation-only edits, inspect consistency, factual qualifications, and links. No application tests are needed.
- For UI implementation, run the project's build and relevant checks, then inspect desktop and mobile screenshots.
- Check approximately 1440px, 768px, and 390px widths, heading hierarchy, keyboard navigation, link targets, overflow, and reduced motion.
- Fix concrete defects in a bounded pass. Do not add tests that simply mirror CSS values.
- Return what changed, what was checked, unresolved content gaps, and preview/screenshot locations.
- Never claim a check passed without running it.
- Commit or push when requested or authorized by the current task. Do not deploy publicly merely because Vercel is mentioned in the brief.

## Collaboration

The planning chat provides positioning, design direction, copy decisions, and implementation prompts. The local coding agent executes the current task using this repository as durable context. Do not assume another chat's history is automatically available.
