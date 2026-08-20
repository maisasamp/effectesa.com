# effectesa.com

One-pager for **Effecte SA** — Swiss industrial software company.

## Products

| Product | Domain | Accent | Status |
|---|---|---|---|
| RapidMech | rapidmech.it | amber `#F59E0B` | live |
| Lisca | lisca.app | blue `#3B82F6` | live |
| Lead Radar | — | green `#10B981` | logo only, page TBD |

## Structure

- `index.html` — self-contained one-pager (all CSS inline, SVG logos inline). English, dark industrial theme.
- `assets/` — standalone SVG logo files for the mark family (Effecte parent mark + 3 product marks, shared geometric system: dark rounded square, 6px strokes, product accent color, steel origin dot).

## Design tokens

- Background `#121519`, raised `#171B21`, lines `#2A313B`
- Text `#E5E7EB`, dimmed `#8B95A3`
- Mono accents: JetBrains Mono fallback stack

## Deploy

Static site — works on GitHub Pages, Netlify, Cloudflare Pages. No build step.
