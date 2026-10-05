# Website content and evidence

Status: initial content inventory, 6 October 2026.
Design direction and project stage are owner-confirmed. Copy below is an initial draft for implementation review, not a claim that every sentence has received final editorial approval.

## Evidence labels

- OWNER: stated directly by Beksultan in the planning conversation.
- CV: present in the supplied Beksultan_Baimagambetov.pdf, read during planning.
- REPO-LIST: repository existence retrieved through GitHub; code has not yet been audited.
- PENDING: needs evidence, owner confirmation, or a supplied asset before publication.

Keep these labels and editorial notes out of the rendered website.

## Identity

- Public name: Beksultan Baimagambetov. [OWNER, CV]
- GitHub: https://github.com/Doppamine [OWNER]
- Education: Nazarbayev University, B.Sc. in Computer Science; expected graduation June 2027. [CV]
- Focus: backend architecture, infrastructure, debugging, and full-stack engineering. [OWNER]
- AI Builders role: CTO and co-founder; project currently at idea stage, with nothing built yet. [OWNER, latest correction]

Do not infer seniority level, years of professional experience, employer endorsement, or startup traction.

## Introduction draft

Descriptor:
Backend / Infrastructure / Full-stack

Headline:
I turn unfamiliar problems into working systems.

Supporting paragraph:
I'm Beksultan, a software engineer and technical co-founder studying Computer Science at Nazarbayev University. I work across backend architecture, infrastructure, and full-stack development.

Actions:
- Explore my work -> selected-work section
- GitHub -> https://github.com/Doppamine

No AI Builders product claim belongs in the headline.

## Selected work: NovaLab

Evidence:
- Co-founded NovaLab and served as CTO. [OWNER]
- Built an interactive 3D educational prototype with React and Three.js. [OWNER, CV]
- Helped guide the transition toward Unity. [OWNER, CV]
- Coordinated two developers, reviewed pull requests, and maintained development and production deployments. [CV]
- Team won Almau Startup Night and the local Babson Student Challenge; participated in ABC Incubation. [OWNER, CV]
- CV lists October 2025-present. Current activity needs confirmation before using "present" in a public timeline. [CV, PENDING]

Draft:
NovaLab
CTO & Full-Stack Developer

I built the first interactive 3D educational prototype with React and Three.js, then helped guide the transition toward Unity. My role also included coordinating two developers, reviewing pull requests, and maintaining separate development and production deployments.

Technology line:
React / Three.js / Unity

Candidate evidence:
- https://github.com/Doppamine/NovaLab_MVP [REPO-LIST]
- https://github.com/Doppamine/CardDemoNovaLab [REPO-LIST]

Pending:
- Which repository/version best represents Beksultan's own work?
- A screenshot or short demo with permission to publish.
- One concrete technical decision and why it was made.
- Exact contribution boundaries after the Unity transition.

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

## Backend candidates: select after review

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

## Currently exploring: AI Builders

Display label:
Currently exploring / Idea stage

Draft:
I'm co-founding AI Builders, a proposed platform for standardized 1v1 AI-building competitions: the same task, time, AI model, environment, and resource limits, with machine-verifiable PASS/FAIL evaluation. My intended responsibility is the technical architecture, backend, infrastructure, and evaluation systems.

Facts:
- Nothing has been built yet. [OWNER]
- The longer-term ambition is a useful performance record for builders and potentially employers. [OWNER; ambition, not an existing feature]

Do not claim a prototype, validated fairness, working evaluator, participants, funding, customers, or live competitions.
Do not state that feasibility research or experiments have already occurred without confirmation.
Keep this section short and secondary to completed work.

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
| NovaLab - CTO & Full-Stack Developer | October 2025-present in CV | Confirm current status before rendering "present" |
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

1. Review the two backend candidates and NovaLab repositories.
2. Record exact evidence paths and contribution limitations.
3. Ask only the remaining factual questions.
4. Promote selected material into concise website copy.
5. Keep any later WSL/Windows discovery report outside the public website repository; bring across only curated publishable facts.

A filesystem scan is a separate, explicitly requested task. This file does not authorize one.
