# Heba Elgendi — Portfolio (GitHub Pages package)

Static site. No build step, no server code.

## Deploy

1. Upload the **contents of this folder** to the repository root (or a `docs/` folder).
2. Repo → Settings → Pages → Source: `Deploy from a branch`, branch `main`, folder `/ (root)` (or `/docs`).
3. Entry point is `index.html`.

## One file you must add yourself

The CV button expects your original PDF at exactly:

```
assets/cv/Heba-Elgendi-CV.pdf
```

Create the `assets/cv/` folder and drop the original PDF in, renamed to `Heba-Elgendi-CV.pdf`.
Do not re-export it — the original keeps its clickable LinkedIn and Behance links.

## Files

- `index.html` — homepage / 90-second experience (also kept as `Heba Elgendy - 90 Seconds.dc.html` so in-page links resolve)
- `Basma|Hawlak|Wajz|Mini Games|SafeHer - Case Study.dc.html` — the five case studies
- `support.js` — runtime, loaded by every page
- `uploads/` — all project covers, screenshots, and the avatar

All internal paths are relative. External dependencies are public CDNs only (Google Fonts, unpkg) — no private or session-bound URLs.
