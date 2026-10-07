# ARCLINE STUDIO — Development Plan

## Recommended Stack
- React
- TypeScript
- Vite
- React Router
- Token-driven CSS architecture
- Native CSS/browser APIs for animation first
- Git + GitHub
- Hostinger for deployment

## Styling Principle
The design-token system is the source of styling truth. Avoid random utility values and duplicated visual rules.

## Folder Architecture
```text
ARCLINE/
├── docs/
├── public/
│   ├── images/
│   │   ├── projects/
│   │   ├── materials/
│   │   ├── studio/
│   │   └── social/
│   └── fonts/
├── src/
│   ├── components/
│   ├── data/
│   ├── layouts/
│   ├── pages/
│   ├── routes/
│   ├── styles/
│   ├── types/
│   ├── hooks/
│   └── utils/
├── README.md
├── package.json
└── index.html
```

## Project Data
Projects should be data-driven with fields such as:
id, slug, number, title, location, type, year, status, concept, intro, context, approach, resolution, materials, images, previousProject, nextProject.

## Routes
/
 /projects
 /projects/:slug
 /studio
 /services
 /approach
 /contact
 /*

## Form
Initial version can implement complete frontend UX and validation without a backend. A real form service can be connected later.

## Animation Architecture
Prefer reusable patterns such as Reveal, ImageReveal, TextReveal and reduced-motion handling. Avoid duplicated animation logic.

## Dependency Policy
Before installing a package, ask:
1. What problem does it solve?
2. Can native CSS/React/browser APIs solve it?
3. Is the problem already solved?
4. What bundle/maintenance cost does it add?
5. Is it necessary?

## AI Studio Modes
ARCHITECT — inspect/propose, minimal implementation.
BUILDER — implement one scoped approved task.
REVIEWER — audit against docs without changing files.

## AI Prompt Contract
Every implementation task should specify:
- What
- Where
- Why/source documents
- What not to touch
- Acceptance criteria

## Build Order
Foundation → Tokens → Global Styles → Layout → Core Components → Homepage → Project System → Secondary Pages → Motion → SEO → Accessibility → Performance → QA → Deployment.

## Task IDs
AR-001 Foundation
AR-002 Design Tokens
AR-003 Global Styles
AR-004 Typography + Layout
AR-005 Navigation
AR-006 Footer
AR-007 Hero
AR-008 Philosophy
AR-009 Projects
AR-010 Materiality
AR-011 Principles
AR-012 Services
AR-013 Approach
AR-014 Studio
AR-015 Editorial
AR-016 Contact
AR-017 Projects Page
AR-018 Project Data
AR-019 Project Detail Template
AR-020–023 Four Projects
AR-024 Studio Page
AR-025 Services Page
AR-026 Approach Page
AR-027 Contact Page
AR-028 404
AR-029 Motion System
AR-030 SEO
AR-031 Accessibility
AR-032 Performance
AR-033 Final QA
AR-034 Deployment

## Quota Protection
- Never ask AI Studio to build the whole site in one request.
- Keep tasks narrowly scoped.
- Reference only the relevant documents.
- Do not ask AI Studio to rediscover project strategy.
- Do not request unnecessary rewrites.
- Describe bugs precisely.
- Review and commit after stable milestones.

## Git
Use main for stable versions and development for active work. Commit after meaningful milestones.

## Security
Never commit secrets, API keys or .env files containing sensitive values.
