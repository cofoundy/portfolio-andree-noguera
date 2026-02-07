# Design Proposal: Andree Noguera Patino

## Analisis
- Profesion: Abogado Penalista (Criminal Defense Lawyer)
- Industria: Legal / Penal / Corporate Compliance
- Audiencia objetivo: Sector corporativo, empresas, clientes potenciales
- Vibe deseado: Prestigioso, serio, confiable, corporativo

## Current State (V1)
- Template: minimal-mono con premium additions (foto circular, legal symbols)
- accentColor: #2d4a7a (navy)
- Font: IBM Plex Mono (monospace - no adecuado para abogado)
- Labels: Spanish (correct - content is Spanish)
- Custom sections: "Destacados" en lugar de "Proyectos"
- Favicon: Generic code brackets (no personalizado)

## Improvements for V2

### 1. Color Palette Upgrade
- Primary: #2d4a7a (navy - keep, projects authority)
- Secondary: #c9a96e (gold accent - prestige, corporate)
- Background: #FFFFFF (white)
- Surface: #FAFAF8 (warm white for cards)
- Text Primary: #1a1a2e (dark)
- Text Secondary: #6b7280 (gray)
- Use gold for subtle accents (dividers, badges, hover states)

### 2. Typography Upgrade
- Headings: Source Serif 4 (serif, legal authority)
- Body: Inter (modern readability)
- Mono: IBM Plex Mono (only for numbered items)

### 3. Section Labels (Spanish)
- Sobre Mi → keep
- Destacados → keep (good legal framing)
- Experiencia → keep
- Educacion → Educacion (add tilde: Formacion Academica?)
- NEW: Areas de Practica (practice areas)

### 4. Section Order
1. Hero (nombre, titulo, foto, social)
2. Sobre Mi
3. Destacados (key cases/achievements)
4. Experiencia
5. Formacion Academica
6. Areas de Practica (new)
7. Footer

### 5. Motion Design
- Hero: fade-in + translateY stagger (existing, keep)
- Sections: IntersectionObserver scroll reveal
- Cards: hover shadow elevation
- Gold accent line animation on section dividers

### 6. Favicon
- AN initials in navy (#2d4a7a) on white background
- Rounded rectangle

### 7. Special Notes
- Add "Estudio Albertini" to experience if confirmed (client mentioned it)
- Highlight corporate focus: compliance, penal economico
- Consider adding contact CTA for corporate inquiries

## Seleccion Final
Keep existing template base, upgrade with:
- Navy + gold palette
- Typography upgrade
- Scroll reveal animations
- Custom AN favicon
- Practice areas section
