# Prestige TV Finder 2026

## What This App Is
A ranked, filterable, mobile-friendly TV recommendation app for 2026. 50 hand-ranked shows with verified RT critic scores, audience scores, refreshed IMDb ratings, and confirmed streaming platforms. Built for Arnie & Ela.

## GitHub Repo
arnoldshapiro-del/prestige-tv-finder-2026

## Live URL
https://prestige-tv-finder-2026.netlify.app

## Tech Stack
- Pure single-file HTML/CSS/Vanilla JavaScript (no framework, no build step)
- PWA: manifest.json included
- Netlify deployment with GitHub auto-sync (main branch)

## Current Status
LIVE — deployed April 2026. Fully functional.

## Features
- 50 ranked shows with RT critic %, RT audience %, IMDb rating, and Taste Fit score
- Visual score bars (green/amber/red thresholds)
- Platform color badges (Max purple, Netflix red, Prime blue, Hulu green, etc.)
- Top 5 cards use full-width two-column layout
- Search, platform filter, type filter, genre/tone filter, multi-sort
- Platform quick-chip strip for one-tap platform filtering
- Favorites (saved to localStorage)
- Copy top 10 to clipboard
- Print / PDF button
- Light/dark mode toggle (saved to localStorage)
- Mobile-friendly, add to home screen / PWA

## IMDb Score Status (as of April 2026)
Verified scores: The Pitt (8.9), A Knight of the Seven Kingdoms (8.7), Industry S4 (7.5), Tehran S3 (7.6), Ponies (7.1), Margo's Got Money Troubles (7.1), Paradise S2 (7.8), For All Mankind S5 (8.1), Shrinking S3 (8.1), The Boys S5 (8.6), The Comeback (7.9), The Fall and Rise of Reggie Dinkins (6.6)
All others: "Not available" — no invented scores.

## File Structure
```
prestige-tv-finder-2026/
  index.html     — complete single-file app
  manifest.json  — PWA manifest
  CLAUDE.md
  SESSION_NOTES.md
```

## Project Rules
- Single file app — keep everything in index.html
- Never invent scores — only real verified numbers or "Not available"
- Deploy workflow: edit → git push → Netlify auto-builds
