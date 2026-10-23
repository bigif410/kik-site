# Site — GitHub Pages

> **Status** — implemented 2026-10-23. This repository owns the public docs page.
>
> The project repository (`kik-server`) is private, so GitHub Pages is hosted from this public
> repository instead.

## Goals

- A visitor understands what kik is within 30 seconds.
- No build step and no external requests (no CDN, no web fonts, no third-party scripts).
- Documentation layout: sidebar, content column, featured cards, edit link.
- Light and dark themes from `prefers-color-scheme`.

## Files

| File | Role |
|---|---|
| `index.html` | Single page: introduction, get started, design, reference |
| `style.css` | Typography and layout; system fonts only |
| `.github/workflows/pages.yml` | Publishes `index.html` and `style.css` to Pages |

## Rules

- English. Identifiers and paths keep their exact spelling.
- Numbers are measured values only (`23.7 tok/s`, `21.1 tok/s`, `6.8–8.1 s`); no promises.
- The project repository is private, so the page does not link to its code.
- No horizontal scroll at 360 px.

## Acceptance

1. Renders with zero external requests.
2. No horizontal scroll at 360 px.
3. Links point to this repository, in-page anchors, or the GitHub profile.
