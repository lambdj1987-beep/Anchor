# ANCHOR 1.1

A private, phone-friendly morning and evening devotional and reflection website.

## Updating GitHub Pages
Upload `index.html`, `sw.js`, `icon.svg` and `manifest.webmanifest` to the **root** of the existing `Anchor` repository, replacing the files with the same names. Do not upload the ZIP itself. GitHub Pages should continue to publish from `main` / `(root)`.

## Journal compatibility
This version deliberately retains the original `localStorage` key `anchor-journal-v1`, original entry shape (`id`, `date`, `time`, `mode`, `reflections`) and backup JSON (`app: ANCHOR`, `version: 1`, `entries`). It does not delete or migrate previous journal data. Export a backup before updating.

The app saves reflections in the browser only; it does not sync between browsers/devices. A reinstall, cleared site data, or different origin can make entries unavailable.

## Content
Seven original themed reading sets rotate by local calendar date. The Scripture text uses KJV passages. Philosophy and recovery explanations are original summaries rather than attributed verbatim quotations or official AA publications. The readings are prepared, not AI-generated.
