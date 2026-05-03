# 2026_Sitio_Corporativo — Context para AI Assistants

## Proyecto

Sitio corporativo de Sivak. Landing page + sitio informativo.

**Ubicación**: `/Sivak-Empresa/01_Proyectos_Web/2026_Sitio_Corporativo/`

## Recurso Compartidos

- **Logos**: `/05_Recursos_Visuales/Logos/Sivak_Logo_Kit.html` (SVG incluido en index.html)
- **Tokens CSS**: `/05_Recursos_Visuales/Brand_Assets/sivak-tokens.css` (integrados en styles.css)
- **Tokens JSON**: `/05_Recursos_Visuales/Brand_Assets/sivak-tokens.json`
- **Brand Book**: `/05_Recursos_Visuales/Brand_Assets/Sivak_Brand_Book.html`

## Design System

### Colores (sivak-tokens)
- `--carbon`: #111110 (primario, texto)
- `--carbon-80`: #2d2d2b
- `--carbon-60`: #5f5e5a (secundario)
- `--carbon-40`: #b4b2a9 (hints)
- `--carbon-20`: #e8e6e1 (bordes, separadores)
- `--parchment`: #f5f3ee (fondo)
- `--white`: #ffffff
- `--success`: #0f6e56

### Tipografía
- **Serif**: DM Serif Display (headings)
- **Sans**: DM Sans (body)
- **Mono**: Space Mono (datos, labels)

### Espaciado Base
- 4px, 8px, 12px, 24px, 48px, 96px

### Border Radius
- sm: 4px | md: 8px | lg: 12px | full: 9999px

## Estructura HTML

### Secciones
1. `<header class="site-header">` — Nav + logo
2. `<section class="hero">` — Hero + meta
3. `<section id="servicios">` — Grid 3 columnas
4. `<section id="nosotros">` — About + stats
5. `<section id="contacto">` — CTA oscuro
6. `<footer>` — Links + copyright

### Componentes
- `.btn` `.btn-primary` `.btn-secondary` `.btn-arrow`
- `.eyebrow` (mono label con línea)
- `.service-card` (hover effect)
- `.hero-meta` (info grid)
- `.stats` (2x2 grid)

## Accesibilidad

- ✅ `aria-label` en nav
- ✅ `aria-labelledby` en secciones
- ✅ `role="list"` en stats
- ✅ Focus visible outlines
- ✅ Color contrast WCAG AA
- ✅ Semantic HTML

## Próximas Fases

1. Integración de contactos (Formspree / Sendgrid)
2. CMS para servicios (si crece)
3. Blog / Case studies
4. Dark mode (opcional)
5. Multilanguage support (ES/EN)

## Equipo

Proyecto inicial. Ver GUIA_CARPETAS.md para convenciones globales.
