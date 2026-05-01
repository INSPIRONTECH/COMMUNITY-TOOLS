# INSPIRON-SUITE — CLAUDE.md

## Project
Community Tools for Manager.io — open-source extensions for the Manager.io
ecosystem. BD-first, multi-regulatory. CPN-visible work.

## Repo
D:\000. REPOS\SECTOR-BRAVO-OPERATIONS\INSPIRON-SUITE

## Stack
- Manager.io API v3 (JSON)
- Next.js 15 · TypeScript · Tailwind CSS
- Vercel (deployment)
- GitHub Pages (static extension hosting where applicable)

## Key Commands
- Build: `npm run build`
- Dev:   `npm run dev`
- Lint:  `npm run lint`

## Folder Structure
```
INSPIRON-SUITE/
├── components/         UI components
├── lib/                Manager.io API client, helpers
├── pages/ or app/      Routes
├── public/             Static assets
├── DOCS/
│   └── STRATEGY/
│       ├── EXECUTION-PHASES.md     ← OPUS writes, SONNET reads
│       └── EXECUTION-REPORTS/      ← SONNET saves reports here
└── CLAUDE.md           ← this file
```

## Off Limits
- `node_modules/` `.next/` `dist/`
- Any `.env` `.key` `.pem` `.manager` file
- Never hardcode Manager.io API keys or business IDs

## Current Phase Status
Phase: NOT STARTED — awaiting first OPUS SUITE planning session

## Coding Rules
- Naming doctrine: ALL-CAPS-HYPHENS for all files and directories
- No raster assets — SVG only for all icons and illustrations
- API calls through `/lib/manager-client.ts` only — never inline
- Locale: en-IN (inherited from Mushak extension work)
- Commit format: `type(scope): short description`

## Extension Context
- First build: Mushak VAT forms (6.3, 6.4, 9.1) — branding complete
- Roadmap: additional BD/PK/UAE compliance tools
- Deployment target: GitHub Pages + tools.inspiron.tech
