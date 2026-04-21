# QR Code Assets

Reusable QR codes for the public landing pages in this repo.

## Why this exists

These files are intended for reuse across:
- slides
- posters
- symposium pages
- conference handouts
- social images or one-pagers

They live in `assets/qr/` on purpose so they are versioned with the repo but are not mixed into the GitHub Pages `docs/` site source.

## Included targets

- `hub-home` → main landing page
- `websci2026` → WebSci 2026 landing page
- `phd-symposium` → PhD symposium landing page
- `judgegpt` → JudgeGPT landing page
- `origin-lens` → Origin Lens landing page
- `judgegpt-live-app` → JudgeGPT live demo
- `origin-lens-app-store` → Origin Lens App Store page

## Formats

Each QR code is exported as:
- `*.svg` for print-quality scaling and design workflows
- `*.png` for quick drop-in use in slide decks and documents

## Recommended usage

- Prefer **SVG** for posters, print, and layouts that may be resized.
- Use **PNG** when a toolchain or app handles raster images more reliably.
- Preserve a clear white margin around the QR code.
- Avoid placing QR codes too close to slide edges or busy backgrounds.
- Link to stable landing pages, not temporary asset files.

## Manifest

See `manifest.json` for a machine-readable index of all QR targets and filenames.
