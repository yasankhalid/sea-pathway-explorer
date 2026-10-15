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

## Learner features (v10)

- **My pathway**: choose a track, tick badges you hold, see progress and your next step (saved in the browser only).
- **Find my track**: a 3-question quiz that suggests a track.
- **English / Arabic** with right-to-left layout (Arabic text is a draft for approval).
- **Learner / Staff mode**: learner mode hides draft labels and "still to be added" placeholders.
- **Tracks view** (a list of courses by track, default on phones), **search**, plain-language term tooltips, course details with an Enrol button, prior-learning note and a digital wallet explainer.

### Editing course details

Open `index.html` and find `var COURSE=` (marked `EDIT HERE`). Fill in `hours`, `format`, `start`, `url`, `outcome_en`, `outcome_ar` for each course. Links for the prior-learning form and wallet help page go in `var LINKCFG=` just below.
