# Anish Katoch — AI/ML Engineer Portfolio

A single-page portfolio site built with plain HTML, CSS, and JavaScript. No framework, no build step, no dependencies beyond a Google Fonts link.

## What's inside

- Animated hero with a gradient headline, a role-rotating typewriter line, and a starfield/constellation canvas
- What I Do, Skills, Experience, Education, Personal Projects, and Contact sections
- Light/dark theme support (follows system preference, overridable), full responsiveness, and `prefers-reduced-motion` support

## Running locally

Just open `index.html` in a browser, or serve it to avoid any `file://` quirks:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project structure

```
index.html   — all markup, styles, and scripts
assets/      — profile photo
```

## Adding or updating the profile photo

Drop an image into `assets/` named one of:

```
profile.jpg
profile.jpeg
profile.png
profile.webp
```

The page checks for these in order and falls back to an "AK" placeholder if none are found — no code changes needed.

## Deploying

This is a static site, so it can be deployed as-is to GitHub Pages, Netlify, Vercel, or any static host by pointing it at `index.html`.
