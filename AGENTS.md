# Instructions for PersonalWebsite

## Project

Personal website for Beksultan Baimagambetov, supporting his founder profile and showing actual engineering work. The chosen visual direction is Engineering Notebook.

Read DESIGN.md and CONTENT.md before implementation. DESIGN.md owns visual and interaction direction. CONTENT.md owns factual copy, evidence status, and missing assets. Current direct user instructions take priority; update the documents when an agreed decision changes.

## Current stage

This repository starts with planning documents only. The current task is to establish those documents. Begin product implementation when the user gives the implementation task; do not scaffold an application just because these instructions exist.

The first requested implementation should be one homepage draft with a polished hero and one complete project entry, followed by screenshot review. The longer homepage structure is in DESIGN.md.

## Factual integrity

- AI Builders is idea-stage; nothing has been built yet. Present it only as a small "Currently exploring" section.
- Use OWNER/CV facts for draft copy while preserving qualifications. Repository existence does not verify implementation or authorship.
- Do not invent results, timelines, architecture, testimonials, clients, tests, metrics, product screenshots, or links.
- Distinguish Beksultan's work from team outcomes.
- Evidence labels and PENDING notes are editorial metadata, not UI copy.
- Omit missing assets or actions cleanly. Ask only when missing input blocks the next meaningful step.
- Keep private background material, credentials, raw personal-file inventories, and internal company information out of this public repository.

## Scope and implementation

- Preserve the Engineering Notebook direction; do not restart aesthetic discovery unless asked.
- Favor static content and minimal client JavaScript. Preserve the existing stack if one is later added; otherwise propose a lightweight Vercel-compatible choice in the implementation response.
- No authentication, database, CMS, analytics, or contact backend is needed for the first draft.
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
