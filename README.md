# OBSCURA® — Independent Digital Designer Portfolio

Conceptual portfolio website built as a complete digital atelier experience.

## Concept

**THE DIGITAL ARTELIER** — an interactive digital workshop where design, spatial objects, light and motion form a single visual universe.

Cinematic dark minimalism · premium digital craftsmanship · experimental editorial typography · sophisticated 3D CGI · subtle sci-fi aesthetics.

## Stack

- React 19 + TypeScript
- Vite
- React Three Fiber + Three.js + Drei
- Framer Motion / GSAP ready
- React Router
- Zod (form validation)
- Lucide icons
- Custom design tokens & CSS

## Features

- Fullscreen hero with interactive 3D sculpture (glass + chrome, parallax, float)
- 8 fictional conceptual case studies with unique art direction
- Filterable work gallery (ALL / WEB DESIGN / BRANDING / 3D / EXPERIMENTAL)
- Individual project pages with editorial layout
- About section with secondary 3D object
- Services list
- Contact form with client-side validation (ready for backend adapter)
- Responsive design, keyboard accessible, reduced-motion support
- SEO meta + Open Graph + favicon
- 404 page

## Project structure

```
src/
  components/     Header, Footer, HeroScene, AboutScene, ContactScene
  sections/       Hero, Work, About, Services, Contact
  pages/          HomePage, ProjectPage, NotFoundPage
  data/           projects.ts (all case study content)
  styles/         tokens.css
public/
  favicon.svg
```

## Getting started

```bash
cd obscura
npm install --legacy-peer-deps
npm run dev
```

Build:

```bash
npm run build
npm run preview
```

## Notes

- All eight projects (AETHER, LUMIÈRE, NØVA, ORBITAL, FORM / OBJECT, SOLACE, AFTERGLOW, MONOLITH) are **fictional conceptual studies**. They are not real client work.
- Contact form validates with Zod and surfaces a clear message that a backend (Resend, Formspree, custom API, etc.) must be connected for delivery.
- 3D scenes use procedural geometry and PBR materials — no external GLB files required.
- Cover visuals are gradient-based compositions matching each project’s art direction.
- Performance: DPR capped, lazy-friendly structure, reduced-motion respected.

## Design system (tokens)

- Background `#080A0F`
- Surface `#11141C` / Elevated `#191D29`
- Text primary `#F5F5F7` / secondary `#9DA3B4`
- Accents: Electric violet `#8B7CFF`, Icy blue `#78C8FF`
- Typography: Syne (display) + Inter (body) + JetBrains Mono

---

OBSCURA® — Designing worlds, not just websites.
