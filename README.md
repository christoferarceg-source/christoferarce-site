# Christofer Arce — Personal Site

Personal portfolio site for [pm-chris-arce.site](https://pm-chris-arce.site), built with plain HTML and CSS. No frameworks, no build step.

## Stack

- HTML5 + CSS3 (custom properties, grid, clamp)
- [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) + [Instrument Serif](https://fonts.google.com/specimen/Instrument+Serif) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts
- Vanilla JS — scroll-reveal (IntersectionObserver) and nav stuck state
- Hosted on GitHub Pages with custom domain

## Structure

```
index.html   — single-page site
styles.css   — all styles, teal accent system (#0d9488)
photo.jpg    — hero portrait
CNAME        — custom domain config
```

## Sections

1. **Hero** — name, tagline, portrait
2. **Logos** — companies built at
3. **About** — background and approach
4. **Track record** — 10+ yrs, 4 markets, 2 zero-to-one products, 3 marathons
5. **Selected work** — credit card, payment rail, cards & data, enterprise
6. **Markets** — MX · BR · CO · US
7. **Beyond** — animated mountain SVG with live fintech counter
8. **Contact** — LinkedIn + email

## Deploy

Pushes to `main` deploy automatically via GitHub Pages.

```bash
git add .
git commit -m "your message"
git push origin main
```

## Design

Originally designed in [Claude Design](https://claude.ai/code), exported as HTML/CSS, and integrated here by stripping prototype-only tooling (`image-slot` web component, React tweaks panel) and wiring in production assets.
