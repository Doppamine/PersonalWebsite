# Personal website: Engineering Notebook

Status: initial implementation brief, 6 October 2026.
The owner selected Engineering Notebook. Exact tokens and composition below are proposed implementation defaults; refine them through screenshot review.
Repository: https://github.com/Doppamine/PersonalWebsite

## Purpose and audience

A personal website for Beksultan Baimagambetov, with the immediate use of supporting a YC founder profile. Help visitors understand his engineering focus, actual contributions, technical judgment, and personality. It should also remain useful to collaborators and employers.

Success: the first viewport explains who Beksultan is and what he does; one short scroll reaches substantive work. Project details distinguish individual contributions from team outcomes. Interested visitors can reach GitHub and contact information without completing the whole narrative.

## Visual direction

Calm, precise, warm, and personal. Think of a carefully typeset engineering notebook with margin notes and clear diagrams. Avoid literal notebook textures or ruled paper behind body copy.

Use an editorial composition: a narrow annotation column beside the main content, generous margins, aligned baselines, subtle separators, and varied project layouts. Technical character comes from explaining actual systems and decisions.

Reference: Almaz Auezov's site established a benchmark for visual consistency and personality. Do not copy its illustrated portraits, torn-paper effects, cinematic chapters, or long introductory sequence.

## Starting tokens

| Role | Value |
| --- | --- |
| Page background | #F7F5EF |
| Raised/paper surface | #FFFEFA |
| Primary text | #242722 |
| Secondary text | #5E655E |
| Accent/link blue | #3157C8 |
| Decorative divider | #D9DDD3 |
| Soft accent surface | #EAF0FF |

Use blue sparingly for links, active states, diagram emphasis, and a single primary action. Decorative dividers do not substitute for accessible control boundaries. Verify actual text and control contrast in implementation.

Typography:
- Main headings and body: locally bundled or framework-managed Inter, with a system sans-serif fallback.
- Annotation labels and technical metadata: IBM Plex Mono, with a monospace fallback.
- Desktop hero: approximately 64-76px, 1.05-1.12 line height, slightly tight tracking.
- Section heading: 32-40px. Project heading: 26-32px.
- Body: 17-18px with 1.55-1.7 line height. Metadata: 12-14px.
- Mobile hero: approximately 38-46px; body: 16-18px.
- Avoid all-monospace paragraphs, excessive uppercase, and ultralight text.

Layout:
- Desktop content maximum: approximately 1160px.
- Desktop outer gutters: at least 48px where space permits; mobile: 20-24px.
- Margin-note column: approximately 140px; remaining space carries the main content.
- Spacing scale: 4, 8, 12, 16, 24, 32, 48, 64, 96px.
- Major desktop sections: around 80-112px vertical separation; mobile: 48-64px.
- Surfaces are mostly flat. Use small radii (4-8px) for controls where helpful; avoid wrapping every paragraph in a card.

## Homepage sequence

### 1. Introduction

Compact navigation with name, Work, About, and GitHub. Use normal anchors. A sticky header is optional; keep it small and prevent anchor targets from hiding underneath it.

Hero:
- Small descriptor: Backend / Infrastructure / Full-stack.
- Name: Beksultan Baimagambetov.
- Primary sentence: "I turn unfamiliar problems into working systems."
- Short introduction from CONTENT.md.
- Primary action: "Explore my work", pointing to selected work.
- Secondary action: "GitHub", using the verified profile URL.
- A modest real portrait may sit to the right when supplied. Until then, compose an intentional text-only hero. Do not invent a portrait or show a broken image placeholder.

Use approximately two-thirds of a desktop viewport, not a mandatory full-screen scene. Hint at the first project below.

### 2. Selected work

Present up to three meaningful entries, not a uniform dashboard grid:
1. NovaLab: initial educational prototype and technical ownership.
2. KeyGroup: production engineering, when a publishable example is identified.
3. One backend project selected after evidence review.

Each entry includes:
- Project name, role, and concise context.
- What Beksultan personally owned.
- A real technical decision, constraint, or outcome when documented.
- Available evidence: repository, demo, screenshot, or approved diagram.
- A small relevant technology line.

Use short summaries first. Longer engineering notes can be in-page details or separate case-study pages later. Do not create empty detail pages or nonfunctional buttons.

A real product screenshot or small annotated diagram can anchor each entry. If no asset exists, use a well-composed text entry. Never fabricate a product UI, benchmark, uptime figure, customer count, or incident.

### 3. Currently exploring

A compact, visually secondary AI Builders section.
Display "Idea stage" clearly. Explain the proposed standardized 1v1 format and Beksultan's intended technical responsibility.
No architecture showcase, fake dashboard, live status, test results, or claims of a working platform.

### 4. About

A brief personal introduction, education, and compact experience timeline.
Use the publishable draft in CONTENT.md. More personal storytelling is optional and requires owner-selected wording. Keep this section human and direct, without motivational slogans.

A debugging case study or "How I work" section may be added after a specific evidenced incident is supplied. It is not required for the first version.

### 5. Contact

GitHub plus email, LinkedIn, and downloadable CV when their publication targets are confirmed.
Never ship placeholder links or an unconnected contact form.
A simple closing line is enough.

## Interaction and responsive behavior

- Normal document scrolling; no scroll hijacking, intro gate, or simulated operating system.
- Optional reveal motion: 150-220ms opacity or very small translation.
- Respect prefers-reduced-motion. Content must remain visible if animation code fails.
- Visible keyboard focus, clear link labels, hover/focus parity, touch targets around 44px.
- Diagrams must have a static readable version and textual explanation.
- On narrow screens, move margin notes above their content and stack split layouts.
- Diagrams should stack or simplify; the page must not scroll horizontally.
- Use semantic landmarks and headings. Test long names and text reflow.
- Keep core content and navigation usable without client-side animation.

## Assets and editorial boundaries

Use actual supplied photographs, screenshots, and demos. Label conceptual diagrams as conceptual and do not imply that planned architecture is deployed.
Do not include customer records, internal domains, private repository links, production credentials, or company configuration in public diagrams.
The reference screenshots and CV are context, not permission to reproduce all their contents as website assets.

## First implementation scope

When the owner gives the implementation prompt:
- Create one homepage draft with the hero, one complete NovaLab entry, and the basic typography/layout system.
- Use simple draft text from CONTENT.md where it is supported.
- The full homepage sequence above is the target, not a requirement to build every section before the first visual review.
- Show desktop and mobile screenshots for composition review before expanding into more project detail.
- Choose a lightweight static-first implementation compatible with Vercel; preserve an existing stack if one is present.
- No CMS, database, authentication, analytics, or contact backend is needed for this draft.

## Review criteria

- Engineering Notebook identity is visible in typography, spacing, margin notes, and content structure.
- Name and engineering focus are immediately understandable.
- Real work precedes AI Builders.
- No invented claims, anonymous placeholders, broken links, or clipped text.
- Check at roughly 1440px, 768px, and 390px, plus keyboard navigation and reduced motion.
- Once an implementation exists, run its build and a bounded browser review. Do not write tests that merely restate styling values.
