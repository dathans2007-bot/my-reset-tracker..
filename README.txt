# 30-Day Reset Tracker (installable web app)

## What this is
This is a Progressive Web App (PWA) package. It can be installed on Android from Chrome once hosted on an HTTPS website. It tracks the challenge from 15 December 2026 through 13 January 2027, with daily habits, cigarette logging, journaling, progress, and backup export/import.

## Important
Opening `index.html` directly from Downloads will not install it as an app. PWA installation requires an HTTPS website (or localhost during development). The tracker stores progress in the browser on the device, so export backups regularly.

## Easiest publishing route: GitHub Pages
1. Extract this ZIP.
2. Sign in or create an account at https://github.com
3. Create a new public repository, for example `reset-tracker`.
4. Upload all files from this folder (`index.html`, `manifest.webmanifest`, `sw.js`, and both PNG icons) into the repository root.
5. In the repository, open Settings → Pages.
6. Under Build and deployment, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
7. Wait for the published HTTPS URL shown on the Pages screen.
8. Open that URL in Chrome on your phone. Use Chrome menu ⋮ → Install app or Add to Home screen.

After installation, the app opens in its own window and can work offline after its first successful load.

## Editing
The page is built from HTML/CSS/JavaScript. Edit `index.html` to change labels, colours, dates, or habits. If changing the challenge dates, also update the date constants in the script. After uploading edits, refresh the app; if an older cached version remains, close/reopen it or clear the site's cache.
