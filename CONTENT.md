# Website content and evidence

Status: updated for the NovaLab YC application, 1 November 2026 (UTC).
Design direction and project stage are owner-confirmed. Copy below is an initial draft for implementation review, not a claim that every sentence has received final editorial approval.

## Evidence labels

- OWNER: stated directly by Beksultan in the planning conversation.
- CV: present in the supplied Beksultan_Baimagambetov.pdf, read during planning.
- REPO-LIST: repository existence retrieved through GitHub; code has not yet been audited.
- SOURCE-REVIEW: specified source files were read; this does not establish runtime behavior, test success, deployment, or sole authorship.
- PENDING: needs evidence, owner confirmation, or a supplied asset before publication.

Keep these labels and editorial notes out of the rendered website.

## Identity

- Public name: Beksultan Baimagambetov. [OWNER, CV]
- GitHub: https://github.com/Doppamine [OWNER]
- Education: Nazarbayev University, B.Sc. in Computer Science; expected graduation June 2027. [CV]
- Focus: backend architecture, infrastructure, debugging, and full-stack engineering. [OWNER]
- Current YC startup: NovaLab; CTO and co-founder. [OWNER, latest correction]
- NovaLab currently has a web MVP and is preparing its first school pilot. [OWNER]
- AI Builders is no longer the focus of this website brief. This does not establish whether that separate idea has been discontinued.

Do not infer seniority level, years of professional experience, employer endorsement, or startup traction.

## Introduction draft

Descriptor:
Backend / Infrastructure / Full-stack

Headline:
I turn unfamiliar problems into working systems.

Supporting paragraph:
I'm Beksultan, CTO and co-founder of NovaLab, where we're building interactive physics labs for schools. I study Computer Science at Nazarbayev University and work across backend architecture, infrastructure, and full-stack engineering.

Actions:
- Explore my work -> selected-work section
- GitHub -> https://github.com/Doppamine

Keep the introduction personal and concrete. NovaLab is the active founder context; do not add YC acceptance, investment, or endorsement claims.

## Selected work: NovaLab

### Current product and stage

Owner-confirmed in the latest planning update:
- Kazakhstan EdTech startup focused on grade-7 physics, with an existing web MVP.
- Teachers create classes, assemble lessons from educational modules, assign labs/simulations/tests, and review activity and results.
- Students enter with a teacher-issued code and PIN, complete interactive lessons and experiments, answer exercises, view progress, and leave lesson feedback.
- The web application includes student accounts, a results journal, and an administrative panel.
- The product supplements teachers and physical laboratory work. Its aim is to make experimentation accessible without adding unnecessary teacher workload.
- Current priorities: low cost, reuse of existing code, rapid feedback cycles, and stability during lessons.
- Broader STEM coverage and international expansion are future ambitions, not present capabilities.

Do not translate desired benefits into established outcomes. "Helps students experiment" describes a capability; "improves grades" requires measured evidence.

### Beksultan's contribution

- Co-founder and CTO; current involvement is confirmed by the latest application update. [OWNER]
- Built the first interactive 3D educational prototype with React and Three.js. [OWNER, CV]
- Helped guide the transition toward Unity. [OWNER, CV]
- Coordinated two developers, reviewed pull requests, and maintained development and production deployments. [CV; historical scope]
- Team won Almau Startup Night and the local Babson Student Challenge; participated in ABC Incubation. [OWNER, CV]

The current platform is a team product. Exact ownership of current backend, deployment, authentication, grading, and Unity integration work still needs attribution before detailed first-person copy. Do not transfer responsibilities previously stated for AI Builders to NovaLab without confirmation.

### Pilot: planned validation

As of this update, the first pilot is scheduled to begin on **3 November 2026**, in the second quarter of the 2026/2027 school year. [OWNER]

Scope:
- One school in Kazakhstan.
- One grade-7 class.
- One physics teacher.
- Free access during the pilot.
- Real classroom use.

The planned evaluation uses tests before and after studying topics, performance data, and teacher/student feedback. The question is whether interactive experiments improve understanding and learning outcomes. No pilot findings have been supplied.

Publication rule: confirm actual status before launch, especially on or after 3 November. Until confirmed, retain explicitly dated planned wording or use "Preparing our first school pilot." Never infer launch, completion, success, paying customers, or causal proof from the schedule alone.

### Draft homepage entry

NovaLab  
CTO & Co-founder  
Interactive physics labs for schools

We're building a platform where students explore physics through virtual experiments, while teachers organize lessons and review results. Our current focus is seventh-grade physics in Kazakhstan.

I built NovaLab's first interactive 3D prototype with React and Three.js, then helped guide its transition toward Unity and coordinate the development team.

Our team now has a web MVP with classes, lessons, interactive modules, and a results journal. We're preparing a free pilot with one school, one seventh-grade class, and one physics teacher to test the approach in real lessons.

Margin note:
MVP / First school pilot planned for 3 November 2026

This wording describes historical personal contributions and current team progress separately. It can be tightened once current contribution boundaries are supplied.

### Technical content

Current product stack supplied by the owner:
Next.js / React / TypeScript / PostgreSQL / Prisma / NextAuth / Unity WebGL / Docker Compose / Caddy.

The owner selected a Kazakhstan VPS for initial production hosting. Do not claim the deployment is already live or reliable under classroom load merely from that selection.

A useful technical decision to develop into a short engineering note:
Students use random identifiers instead of full names, and the school keeps the mapping to real students. NovaLab stores learning results associated with those identifiers. Describe this as reducing collected identifying information, not full anonymity or a legal-compliance guarantee. [OWNER]

Keep public technical explanations at this level until exact implementation and personal ownership are confirmed. The product stack does not determine the personal website stack.

### Evidence and assets

- Current product repository was located through the owner's supplied link; it is private. Do not publish its URL, source excerpts, internal documentation, or operational details here or in the website.
- Limited repository review found core Next.js, React, Prisma, and authentication dependencies consistent with the owner's description. No build, runtime flow, deployment, or security audit was performed. Public copy remains based on the owner's supplied facts.
- Historical public repository candidates:
  - https://github.com/Doppamine/NovaLab_MVP [REPO-LIST]
  - https://github.com/Doppamine/CardDemoNovaLab [REPO-LIST]
- These historical links are not automatically evidence of the current MVP. Confirm which represents the original prototype before linking it in the rendered entry.

Pending:
- Exact current contributions Beksultan personally owns.
- One concrete technical decision, rationale, and supported outcome.
- A real screenshot or short demo cleared for publication, with student records removed.
- A public product/demo URL if available.
- Actual pilot status at publication time.

Awards are optional secondary evidence. Keep local Babson results distinct from global-stage results; do not relabel a local win as winning the global competition.

## Selected work: KeyGroup

Evidence:
- Full-Stack Developer & DevOps Engineer, July 2026-present in the CV. [OWNER, CV]
- Worked across five production projects. [CV]
- Supported infrastructure migration and post-migration checks for seven production domains. [CV]
- Verified Nginx routing, PM2 processes, ports, and deployed releases. [CV]
- Troubleshot Linux services and deployment workflows; built JavaScript/TypeScript developer tooling and supported CI/CD and release verification. [CV]
- Docker staging was in progress when the CV was written; completion has not been established. [CV]

Draft:
KeyGroup
Full-Stack Developer & DevOps Engineer

I work across web, backend, and infrastructure repositories, supporting releases and troubleshooting production services. My work has included migration checks, developer tooling, and deployment verification.

Pending:
- Confirm current role wording at publication time.
- Select one specific contribution suitable for public discussion.
- Capture the problem, investigation or decision, contribution, and verified outcome.
- Confirm which company/project names and diagrams may be published.

Do not imply Beksultan solely designed or migrated all systems. Do not invent performance improvements or publish internal topology.

## Supporting engineering candidates: select after review

### Supplier-consumer backend

CV evidence:
- Python, Django, PostgreSQL, Docker.
- Led a three-person backend team.
- Modular monolith with 26 REST API endpoints.
- UML planning, OpenAPI/Swagger interface documentation.
- Containerization and unit/feature tests.

Candidate repository:
https://github.com/Doppamine/Django_Project [REPO-LIST; project mapping PENDING]

### Laravel marketplace

CV evidence:
- PHP, Laravel, PostgreSQL, Docker.
- In development when the CV was written.
- 17+ REST API endpoints.
- Separate user and company storefronts.
- Role-based access using Laravel Policies.
- Docker Compose with PHP, Nginx, PostgreSQL, and Mailpit.

Candidate repository:
https://github.com/Doppamine/loyalty-marketplace-api [REPO-LIST; project mapping PENDING]

The candidate URLs are leads, not verified mappings. Inspect README, source structure, relevant implementation, and Git history before linking either as a case study.
Do not select a project based on endpoint count alone. Prefer clear ownership, meaningful decisions, working behavior, and accessible evidence.

### Recruitment/CV application candidate

Repository:
https://github.com/Doppamine/ItransitionProject

Limited source review at commit `5c6cb25eb4927ab42309eceb0868e08b984fc02b`:
- `composer.json` declares PHP, Symfony, Doctrine, Twig, PostgreSQL support, and OAuth client dependencies.
- `src/Controller/CVController.php` contains CV creation and publication flows, authorization checks, CSRF checks, and version-aware autosave using optimistic locking with a conflict response.
- The source tree contains profile/position modules and tests. Test presence does not establish that they pass.
- This is a potentially useful case study about editing shared profile data and handling concurrent changes. [SOURCE-REVIEW; case-study selection is an editorial inference]

Source permalinks:
- https://github.com/Doppamine/ItransitionProject/blob/5c6cb25eb4927ab42309eceb0868e08b984fc02b/composer.json
- https://github.com/Doppamine/ItransitionProject/blob/5c6cb25eb4927ab42309eceb0868e08b984fc02b/src/Controller/CVController.php

Pending: confirm the project's public name, Beksultan's contribution boundaries, one decision he can explain, and a usable demonstration. No runtime checks were performed. Do not describe this as an employer's production system or proof of employment at Itransition.

Choose at most one of these candidates for the initial homepage. Prefer an explainable engineering decision and clear ownership over endpoint counts or number of technologies.

## Earlier idea: AI Builders (editorial history only)

The previous brief featured AI Builders, an idea-stage competition platform with nothing built at that time. The owner has changed the YC application to NovaLab. Remove AI Builders from the default homepage and hero; do not describe it as abandoned or make new status claims.

## About draft

I first became interested in computers through games and figuring out how things worked. I learned programming at Yandex Lyceum, later returned to it through C# and Unity, and now work across web products and infrastructure.

I enjoy problems that cross technical boundaries: understanding an unfamiliar system, investigating why something fails, and turning an unclear requirement into something usable.

Education line:
Nazarbayev University / B.Sc. Computer Science / Expected June 2027

Do not add more intimate autobiographical material or a detailed personal story until the owner chooses the public wording. Personal history supplied for planning is not automatically homepage copy.

## Experience timeline

| Role | Dates from evidence | Publication note |
| --- | --- | --- |
| KeyGroup - Full-Stack Developer & DevOps Engineer | July 2026-present | Confirm current at launch |
| NovaLab - CTO & Co-founder | October 2025-present | Current involvement owner-confirmed in latest update; check again at launch |
| iKapitalist - Software Engineer Intern | March-June 2025 in CV; March-July 2025 in owner message | Resolve discrepancy; use "2025" if needed for an initial draft |

iKapitalist CV evidence: designed and executed 30+ Quick Loan test scenarios and helped investigate/resolve 10+ high-priority bugs. Do not imply ownership of the entire feature.

Do not add other employers from memory or unrelated accounts without owner confirmation.

## Contact and assets

Ready:
- GitHub: https://github.com/Doppamine

Pending publication choices:
- Preferred public email.
- Confirmed LinkedIn URL.
- Which CV version to publish, including the internship date correction.
- Optional portrait and NovaLab media.
- Final domain.

Until supplied, omit unavailable actions instead of using "#" links, invented addresses, stock portraits, or fake demos.
Do not upload the full CV automatically; its contact details and final publication version need deliberate selection.

## Next evidence pass

1. Confirm NovaLab contribution boundaries, obtain one approved visual, and recheck pilot status.
2. Choose one supporting engineering project; record source evidence and contribution limitations.
3. Ask only the remaining factual questions.
4. Promote selected material into concise website copy.
5. Keep any later WSL/Windows discovery report outside the public website repository; bring across only curated publishable facts.

A filesystem scan is a separate, explicitly requested task. This file does not authorize one.
