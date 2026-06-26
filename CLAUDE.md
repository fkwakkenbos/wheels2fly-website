# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

Single-page marketing website for **Wheels 2 Fly** — a modular flat-pack wheelchair project by Thomas Maas and Johan Nieuwendijk, targeting deployment in Zambia and beyond.

## Stack

- Plain HTML (`index.html`) — no build step, no bundler
- **Tailwind CSS** via CDN (configured inline with a custom theme)
- **Alpine.js** via CDN (used for the mobile nav toggle)
- **Space Grotesk** font via Google Fonts

## Running locally

Open `index.html` directly in a browser, or serve with any static file server:

```
npx serve .
# or
python3 -m http.server
```

## Design tokens (Tailwind theme)

| Token | Value |
|---|---|
| `ink` | `#1B1C20` |
| `cream` | `#F7F6F3` |
| `muted` | `#5C5E66` |
| `purple.brand` | `#6B3FA0` |
| `purple.vivid` | `#8B5CF6` |
| `purple.light` | `#EDE8F7` |
| `purple.tint` | `#F0EBFA` |
| `purple.deep` | `#5B2F90` |

## Page sections

`#hero` → `#challenge` → `#product` (Rölli) → `#how` (approach) → `#impact` → `#team` → `#partners` → footer

## Image placeholders

Hero and product sections contain striped placeholder divs (`.stripe-dark` / `.stripe-light`) awaiting real product photography. Replace the placeholder `<div>` blocks with `<img>` tags when photos are available.

## Design source

Original design lives at `claude.ai/design` project `d153a9dd-7413-47a1-8a06-12ce08d47236` (file: `wheels2fly-export.html`).
