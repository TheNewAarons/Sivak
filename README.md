# 2026_Sitio_Corporativo

Sitio corporativo de Sivak — Empresa chilena de desarrollo de software.

## Estructura

```
├── index.html       # HTML principal
├── styles.css       # Estilos (design tokens integrados)
├── public/          # Archivos estáticos (imágenes, assets)
├── src/             # Código fuente (si se amplía a SPA)
└── tests/           # Tests
```

## Recursos

- **Logo**: Integrado desde `/05_Recursos_Visuales/Logos/Sivak_Logo_Kit.html`
- **Tokens**: Basados en `/05_Recursos_Visuales/Brand_Assets/sivak-tokens.css`
- **Tipografía**: DM Serif Display, DM Sans, Space Mono (Google Fonts)

## Colores

- **Carbon** (#111110) — Primario, texto
- **Parchment** (#f5f3ee) — Fondo
- **White** (#ffffff) — Cards, inputs
- **Success** (#0f6e56) — Estados positivos

## Desarrollo

```bash
# Abrir en navegador
open index.html
```

## Secciones

1. **Hero** — Introducción principal con meta info
2. **Servicios** — Web, ERP, SaaS
3. **Nosotros** — About + estadísticas
4. **Contacto** — CTA final
5. **Footer** — Links + copyright

## Next Steps

- [ ] Integrar con gestión de contactos
- [ ] Analytics (Google Analytics / Plausible)
- [ ] Formulario de contacto funcional
- [ ] Optimización SEO + Open Graph
- [ ] Tests de accesibilidad (WCAG AA)
