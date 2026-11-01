# Beksultan's personal website

First visual draft of the Engineering Notebook homepage: introduction, NovaLab,
and GitHub. Astro renders static HTML and CSS with no client JavaScript. TypeScript
holds structured content; Inter and IBM Plex Mono are bundled locally through
Fontsource. The `dist/` output is suitable for Vercel's Astro preset, without a
server adapter.

## Local development

Use Node.js 22.12+ and npm.

```sh
npm ci
npm run dev -- --host 127.0.0.1
```

Open http://127.0.0.1:4321. To check and preview the production output:

```sh
npm run check
npm run build
npm run preview -- --host 127.0.0.1
```

## Editing

- `DESIGN.md` owns visual direction; `CONTENT.md` owns supported facts and gaps.
- `src/content/home.ts` contains publishable copy and the manually maintained
  pilot status. A scheduled date must never automatically imply a pilot launch.
- `src/pages/index.astro` composes the page; `src/components/` contains the
  notebook row, project entry, and arrow; `src/styles/global.css` owns styling.
- No portrait, product screenshot, public demo, email, or CV action appears until
  an approved asset or destination is supplied. Current personal contribution
  details and pilot status need confirmation before publication.

Do not publish private product source or repository links. No deployment,
analytics, backend, or contact service is configured.
