# Desert Preflight

A self-contained, browser-based artwork preflight tool for small-business print jobs. Retro Palm Springs desert-night aesthetic, dark mode, works great on mobile and desktop.

## What It Does

Upload (or drag-and-drop) an image and pick a print size. Desert Preflight instantly tells you:

- **Effective DPI** with a visual score meter
- **Print quality grade** — Excellent / Usable / Risky / Rescue Needed
- **Warnings** — low resolution, aspect ratio mismatch, missing bleed, RGB color mode, text-too-small risk, compression artifacts
- **Client-safe explanation** — plain English summary you can copy and paste to a client
- **Rescue plan** — actionable next steps based on detected issues (resize, AI upscale, request originals, paper stock tips, etc.)

## How to Use

1. Open `index.html` in any modern browser — no server needed.
2. Try a **demo sample** to see how it works, or upload your own artwork.
3. Pick a **print preset** (business card, postcard, flyer, poster, banner) or enter custom dimensions.
4. Set **viewing distance** and **bleed** if applicable.
5. Hit **Analyze Artwork**.
6. Review the score, warnings, and rescue plan. Copy the client explanation to your clipboard.

## Features

- 100% local — nothing leaves your browser
- No dependencies, no build tools — single HTML file
- Common print presets built in
- Viewing distance adjusts DPI requirements (handheld vs. wall vs. banner)
- Bleed-aware calculations
- Demo mode with sample artworks
- Copy-to-clipboard for client communication
- Mobile-friendly responsive layout
- Subtle star field animation and desert-night color palette

## Tech

Pure HTML/CSS/JS. Uses the browser's native Image API to read pixel dimensions. All heuristics are clearly labeled as estimates.

Built for [Inspired Design](https://nsprd.com) · Palm Springs, CA
