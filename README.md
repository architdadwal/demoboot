# Northstar AI Bootcamps — React UI prototype

A responsive, four-page React/Vite website concept for AI and machine-learning bootcamps aimed at working professionals in the US. The design uses custom CSS (no Tailwind), Framer Motion, Lucide icons, and remote Unsplash imagery.

## Pages
- `/` — Landing page, hero, program cards, learning process, outcomes, CTA
- `/programs` — Bootcamp catalog with category filters
- `/program/:slug` — Udemy-inspired course detail with expandable curriculum modules and lesson rows
- `/faculty` — Learning philosophy and faculty/curriculum page

## Interaction included
- Responsive mobile navigation
- Animated hero artwork, floating cards, hover states, and scroll reveals
- Filterable course catalog
- Expand/collapse curriculum modules
- Clicking any lesson opens the create-account modal
- Account modal has signup/sign-in mode, form validation, and demo success state
- Start-learning CTAs open the same account flow

## Run locally
```bash
npm install
npm run dev
```

For a production build:
```bash
npm run build
npm run preview
```

## Important launch notes
- Authentication is a front-end demo. Connect a real auth provider and backend before launch.
- Tuition, ratings, reviews, learner quotes, and course outcomes are illustrative prototype content, not verified business claims.
- The faculty page deliberately does **not** claim a partnership with a real university or professor. Replace the faculty placeholder with a confirmed instructor biography, approved image, credentials, and affiliation before publishing.
- Images currently load from Unsplash URLs and require an internet connection. For production, confirm usage rights, optimize, and self-host licensed assets.
- Update Terms, Privacy, contact details, enrollment, checkout, analytics, and email flows before launch.
