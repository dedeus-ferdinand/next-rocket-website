# Design System — Next Rocket Landings

Estilos compartidos para que todas las landings (producto.nextrocket.io y futuras) mantengan el mismo branding y UI/UX.

## Orden de carga (en cada landing)

1. **tokens.css** — Variables de marca: colores, gradientes (`--midnight-blue`, `--gradient-primary`, etc.).
2. **layout.css** — Reset, `body`, `.container`, `.section`, `.section-lg`, `.is-hidden`.
3. **components.css** — Componentes: nav, botones, pastilla, hero, video, phrase-block, cards, pricing, zigzag, footer y media queries.

## Uso en una nueva landing

En el `<head>`:

```html
<link rel="stylesheet" href="design-system/tokens.css">
<link rel="stylesheet" href="design-system/layout.css">
<link rel="stylesheet" href="design-system/components.css">
```

Las fuentes (Poppins, Mulish, Caveat) se cargan desde Google Fonts en cada página.

## Componentes disponibles

- **Nav:** `.nav-landing`, `.nav-landing-inner`, `.nav-burger`, `.nav-drawer` (móvil)
- **Botones:** `.btn`, `.btn-primary`, `.btn-secondary`, `.btn-group`
- **Pastilla:** `.pastilla`, `.pastilla-secundaria`
- **Hero:** `.hero`, `.hero-label`, `.hero-headline`, `.hero-sub`, `.hero-cta`
- **Secciones:** `.section`, `.container`, títulos (`.section-title-frase`, `.section-heading-left`)
- **Cards:** `.service-card`, `.pricing-card`, `.cta-card`
- **Footer:** `.footer`, `.footer-cta`, `.footer-copy`

Cambios de marca (colores, gradientes) se hacen en **tokens.css** y aplican a todas las landings.
