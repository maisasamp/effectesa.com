# effectesa.com

One-pager for **Effecte SA** — industrial software company.

## Products

| Product | Domain | Accent | Status |
|---|---|---|---|
| RapidMech | rapidmech.it | steel blue `#5B8DC6` | live |
| Lisca | lisca.app | orange `#E58133` | live |

## Services

| Service | Domain | Accent | Notes |
|---|---|---|---|
| Orbitale | orbitale.app | blue `#5B8CF2` / amber `#F59E0B` | human-supervised service, own section on the page |

## Structure

- `index.html` — self-contained one-pager (all CSS inline, SVG logos inline). English, dark industrial theme.
- `leadradar.html` — legacy URL, kept only as a noindex redirect to https://orbitale.app.
- `assets/` — official RapidMech wordmark (SVG), official Lisca logo (PNG, transparent), Effecte marks (SVG).

## Design tokens

- Background `#121519`, raised `#171B21`, lines `#2A313B`
- Text `#E5E7EB`, dimmed `#8B95A3`
- Mono accents: JetBrains Mono fallback stack

## Deploy

Static site served by Caddy on the Hetzner server (`/home/deploy/effectesa.com`, `git pull` after push). No build step.
