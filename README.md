# ScoreMaxx AI — scoremaxxai.com

The entire site is one file: `index.html`. Netlify deploys this repo automatically —
whatever `index.html` says on the `main` branch IS the live site.

## To update the site

1. Get the new `index.html` (from Claude or your own edit).
2. In this repo click **Add file → Upload files**, drag the new `index.html` in
   (same name — it replaces the old one), write one line about what changed,
   and press **Commit changes**.
3. Netlify deploys it automatically within about a minute. Done.

## To roll back

Open **Deploys** in Netlify, click any older deploy, press **Publish deploy**.
Or in GitHub: open the commit history of `index.html` and revert.

## Rules that keep this safe

- **Never** deploy by drag-and-drop into Netlify again — the repo is the only door.
- Every past version lives in the commit history, so nothing is ever lost.
- To hand Claude the current site, download `index.html` from this repo —
  never from your Downloads folder.
