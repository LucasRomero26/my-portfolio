# Lucas Romero — Portfolio

Personal portfolio of **Lucas Romero**, AI/ML Engineer & Full-Stack Developer.

Live site: [lucasromero.site](https://lucasromero.site)

## Overview

A single-page, static portfolio (no build step) featuring selected projects,
experience, skills, and a downloadable ATS-friendly CV. Built with plain HTML,
CSS, and JavaScript, including a WebGL fluid background.

## Structure

```
.
├── index.html            # The entire site (HTML + CSS + JS inline)
├── Lucas_Romero_CV.pdf   # ATS-friendly CV (opens from the "View CV" button)
├── KillaAssistant.png    # Project preview images
├── EpiGuard.png
├── Granger.png
└── SugarcaneLeaf.png
```

## Deploy (Vercel)

This is a zero-config static site. On Vercel:

1. Import this repository.
2. Framework Preset: **Other** (no build command, no output directory needed).
3. Deploy — Vercel serves `index.html` at the root automatically.

## Local preview

Just open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```
