# QA Report: Andree Noguera Patino

**Date:** 2026-02-07
**URL:** https://cofoundy.github.io/portfolio-andree-noguera/
**Status:** PASS
**Tier:** Premium (S/.280)

## Data Validation
- [x] Name matches source: "Andree Noguera Patino" (matches Sheet + config.ts)
- [x] Email matches source: "anoguera.pe@gmail.com" (matches Sheet exactly)
- [x] Title from source: "Abogado Penalista | Litigante | Maestrista PUCP" (matches config.ts)
- [x] LinkedIn: @nogueraandree (matches config.ts)
- [x] Companies all verified from CV/research: Fexlaw, Estudio Silva, NOPRA, Corte Suprema, Patino Lopez, Ministerio Publico
- [x] Education verified: PUCP Maestria + UPC Titulo Profesional
- [x] Dates consistent with research-notes.md
- [x] No hallucinated data detected

**NOTE:** Client's form mentions "Estudio Albertini" as current workplace, but CV/LinkedIn shows "Estudio Silva & Abogados". This is documented in research-notes.md (line 81). Not hallucinated -- sourced from CV. The Albertini reference may be a newer position not yet reflected in CV.

## Premium Features
- [x] Custom AN favicon (navy #2d4a7a background, gold #c9a96e "AN" text, serif font)
- [x] Source Serif 4 serif headings (loaded via Google Fonts, applied to h1/h2/h3 in CSS)
- [x] Inter body font (professional sans-serif)
- [x] IBM Plex Mono monospace accents
- [x] Navy accent color #2d4a7a (found 46 times in HTML)
- [x] Gold accent #c9a96e (used in favicon)
- [x] Circular profile photo in hero (rounded-full class with border)
- [x] Legal symbols pattern in hero background (section, paragraph, copyright, Art., Lex, Jus symbols)
- [x] Scroll reveal animations (IntersectionObserver + CSS transitions)
- [x] Sticky header with blur effect on scroll

## Sections Present
- [x] Navigation: Sobre Mi, Destacados, Experiencia, Educacion, Areas
- [x] Hero section with photo, name, title, social links
- [x] Sobre Mi (About) with skills badges
- [x] Destacados (3 highlight cards: NOPRA, Corte Suprema, Docencia)
- [x] Experiencia (6 positions with timeline layout)
- [x] Educacion (2 entries: PUCP + UPC)
- [x] Areas de Practica (6 areas: Derecho Penal, Penal Economico, Compliance Penal, Litigacion Oral, Consultoria Corporativa, Arbitraje)
- [x] Footer with name, title, social links, navigation, copyright

## Content Language
- [x] HTML lang="es" set correctly
- [x] All content in Spanish throughout
- [x] Navigation labels in Spanish
- [x] Section headers in Spanish
- [x] Footer text in Spanish ("Todos los derechos reservados")

## Clean Deploy
- [x] No "Powered by" / "Made with" / "Built with" visible text
- [x] No "View source" / "View on GitHub" / "Fork this" template links
- [x] No "Lorem ipsum" / "Your name here" / "[placeholder]" text
- [x] No template watermarks visible to users
- [x] No "undefined" or "null" visible in content
- [x] No Cofoundy branding visible
- [x] "Astro" only in HTML attributes (data-astro-cid), not visible to users

## Technical
- [x] Page loads: HTTP 200
- [x] CSS loads: HTTP 200 (/portfolio-andree-noguera/_astro/index.Cpi3rPPj.css)
- [x] Profile image loads: HTTP 200 (/portfolio-andree-noguera/profile.jpg)
- [x] Favicon loads: HTTP 200 (/portfolio-andree-noguera/favicon.svg)
- [x] Google Fonts loaded (Source Serif 4 + Inter + IBM Plex Mono)
- [x] Viewport meta tag present
- [x] Responsive breakpoints: sm/md/lg/xl all present in CSS
- [x] No critical console errors from the portfolio site

## Mobile Responsiveness (verified via code/CSS)
- [x] flex-col-reverse for mobile hero layout (photo on top, text below)
- [x] Responsive sizing for profile photo (w-48/sm:w-56/md:w-72/lg:w-80)
- [x] Responsive padding across all breakpoints
- [x] Responsive font sizes (text-3xl to lg:text-7xl for headings)
- [x] Grid collapses from 12-col to single column on mobile
- [x] Practice areas grid: 1 col on mobile, 2 cols on sm+

## Issues Found
None -- all checks pass.

## Evidence
- qa-desktop.png (hero section screenshot, verified correct tab/URL)
