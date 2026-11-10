# Excalidraw Drive Sync guide

A dedicated public introduction and guide for the Excalidraw Drive Sync Chrome extension. Published with GitHub Pages at https://yck2024.github.io/excalidraw-drive-sync-guide/ after merge and Pages setup.

The site is plain HTML and CSS, with no build step, JavaScript, analytics or remote font dependencies. Its five pages are Home, Setup, Release notes, FAQ & support, and Privacy. All paths are relative so the site works under the GitHub Pages repository prefix.

## Preview locally

From this repository directory:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open http://127.0.0.1:8000/. Use your browser's light/dark appearance and a narrow viewport to preview both themes and the phone layout. Screenshots link to their full-size WebP versions.

## Content and assets

- Extension behavior, privacy and permissions: `yck2024/excalidraw-drive-sync`, `origin/main` at `54ebcf9`, `docs/store/1.2.0/` and `docs/decisions/`.
- Earlier version history: `e8f9c4d` (1.0.0) and `051e88b` (1.1.0). Dates in release notes are source-history dates, not asserted store publication dates.
- Layout approach: `yck2024/ai-prompt-assistant` public guide: shared navigation, card grids, numbered steps, notes, screenshot frames, reading columns and native FAQ disclosures. Recolored and adapted for this extension.
- Brand: approved Excalidraw Drive Sync Soft kit, including `assets/css/tokens.css`, hand-sketched SVG marks and the cloud-plane doodle. Website type uses the extension's self-hosted Assistant fonts; license in `assets/fonts/OFL.txt`.
- Store screenshots: all five approved 1280×800 version 1.2.0 screenshots, converted to WebP with accurate descriptions. The existing doodle was resized to 480px, its faint background haze made fully transparent, and converted to WebP. No new generated artwork.
- Privacy policy and contact details: [Privacy](privacy.html).

See [Release notes](release-notes.html#v1-2-0) for version 1.2.0 availability and [the release-label decision](docs/decisions/0003-release-status.md) for verification requirements.

Decisions are recorded in [docs/decisions](docs/decisions/README.md). Publishing GitHub Pages and updating the existing personal-site link are separate follow-up actions.
