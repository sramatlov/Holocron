# Holocron

A chronological Star Wars rewatch tracker with per-episode progress, scores and reception notes. Built as a single self-contained web app that runs entirely in your browser, with no account, server or internet connection required after loading.

## What it does

Holocron lists the main saga films, spin-off films and live-action shows in chronological story order, so you can work through the rise of the Sith, the fall of the Republic, the growth of the Rebellion and the New Republic era in one continuous timeline.

For each title you can:

- Mark films as watched, or check off individual episodes for the shows
- See live progress: titles done, episodes done, hours watched and hours remaining
- Track an unbroken "streak" of consecutively watched titles from the start of the timeline
- Read a synopsis, key characters, release year, format and era
- Compare IMDb, Rotten Tomatoes critics and audience scores, with a critic-versus-audience split indicator and the official critics consensus

Shows are grouped into their story eras (High Republic, Fall of the Republic, Reign of the Empire, Age of Rebellion, The New Republic, Rise of the First Order), each with its own accent colour. A "Up Next" banner always surfaces the first unwatched title so you know where to pick up.

## Features

- Per-episode tracking for all ten live-action shows, with a title auto-completing once every episode is checked
- Filters for films, series, or everything still to watch
- Progress saved locally in your browser via `localStorage`
- Export and Import buttons to back up your progress as a small JSON file and restore it later
- Mobile-first layout, installable to your home screen as a PWA

## Getting started

Open `index.html` in any modern browser. That is the whole app.

To use it as a proper app on your phone with a home-screen icon and reliable storage, host the files on GitHub Pages and install it from Chrome. Step-by-step instructions are in `LEES-MIJ.md`.

### Files

- `index.html` — the app
- `manifest.json` — PWA manifest for home-screen install
- `icon-192.png`, `icon-512.png` — app icons
- `LEES-MIJ.md` — installation instructions (Dutch)

## Your data

Progress is stored on your own device, never uploaded anywhere. The Export button writes a `star-wars-progress.json` backup you can keep or move between devices; Import loads it back. The Reset button clears everything.

## Notes

Runtimes and scores are approximate and can shift over time, especially audience scores and anything recently released. Rotten Tomatoes figures are critics' Tomatometer scores unless labelled as audience scores.

May the Force be with you.







