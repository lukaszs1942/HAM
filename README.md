# HAM Knowledge

A simple repository for organizing amateur radio and HAM knowledge in a clean, easy-to-read structure.

Live site: https://lukaszs1942.github.io/HAM/

## Purpose

This project is intended to present core HAM topics as a readable knowledge base, with simple sections that can be expanded over time.

## Contents

- `index.html` — landing page with core topics and a study plan
- `style.css` — shared layout and colors used by every page
- `docs/propagation.html` — radio propagation guide (PL)
- `docs/KF/zakladki.html` — HF bookmarks: propagation, spots and solar data tools (PL)
- `docs/KF/band-plan-poland-hf.html` — HF band plan for Poland, FT8 frequencies, WSJT-X colors (PL)
- `docs/morse-trainer.html` — Morse/CW trainer: Koch drills, character chart, straight key (EN)

## Open locally

Open `index.html` in a browser. All links are relative, so the site works the same locally and on GitHub Pages.

## Deployment

Every push to `main` deploys the repository to GitHub Pages via `.github/workflows/deploy-pages.yml`.

## Adding a page

Link the shared stylesheet with a relative path (e.g. `../style.css` from `docs/`), keep page-specific rules in an inline `<style>`, and add the page to the nav in every page.

## Suggested future structure

- `reference/` — frequency and equipment references
- `study/` — beginner study plans
- `logs/` — operating or practice logs
