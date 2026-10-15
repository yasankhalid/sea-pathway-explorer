# SEA Learning Pathway Explorer

Interactive explorer of the SEA Learning Pathway Framework (v0): the Core, seven tracks, five levels, shared credits and the SEA badge set.

## Contents

| Path | What it is |
|---|---|
| `index.html` | The explorer page. Open it in a browser. |
| `badges/` | Badge images the page displays. Keep this folder next to `index.html`. |
| `badge-files/png/` | 400×400 PNG badges for uploading to Parchment. |
| `badge-files/svg/` | Square SVG badges (text as outlines). |

## View it locally

Double-click `index.html`, or open it in Chrome, Edge or Safari.

## Publish with GitHub Pages

1. Create a repository on GitHub (for example `sea-pathway-explorer`).
2. Upload everything in this folder to the repository root and commit.
3. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/sea-pathway-explorer/`.

## Updating the content

The framework data (levels, tracks, credentials, shared credits) is defined near the top of the script in `index.html`, in the `TRACKS`, `LEVELS` and `ITEMS` lists. Badge images are mapped to credentials in the `BADGE` and `LVBADGE` lists.

Fonts load from Google Fonts, so the page looks best with an internet connection.

Arabic badge titles are draft translations and should be approved before official use.
