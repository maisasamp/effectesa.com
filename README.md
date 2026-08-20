# effectesa.com

One-pager for **Effecte SA** — industrial software company.

## Products

| Product | Domain | Accent | Status |
|---|---|---|---|
| RapidMech | rapidmech.it | steel blue `#5B8DC6` | live |
| Lisca | lisca.app | orange `#E58133` | live |
| Lead Radar | — | green `#10B981` | user-access page (`leadradar.html`) |

## Structure

- `index.html` — self-contained one-pager (all CSS inline, SVG logos inline). English, dark industrial theme.
- `leadradar.html` — Lead Radar user-access page (static sign-in placeholder).
- `assets/` — official RapidMech wordmark (SVG), official Lisca logo (PNG, transparent), Lead Radar badge + Effecte parent mark (SVG).

## Design tokens

- Background `#121519`, raised `#171B21`, lines `#2A313B`
- Text `#E5E7EB`, dimmed `#8B95A3`
- Mono accents: JetBrains Mono fallback stack

## Deploy

Static site — works on GitHub Pages, Netlify, Cloudflare Pages. No build step.
