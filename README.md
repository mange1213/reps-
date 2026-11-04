# Sales Representative Reports — Install-ready package v6

Target GitHub Pages site: https://mange1213.github.io/reps/
Repository: https://github.com/mange1213/reps

## Publish the complete package
1. Extract this ZIP.
2. In the repository, replace the existing root `index.html`, `manifest.json`, and `sw.js`; upload/replace the complete `icons/` folder too.
3. Keep GitHub Pages configured to publish the repository root (or change the paths in the manifest if you publish from another folder).
4. Wait for the Pages deployment to finish.
5. Verify these URLs load without a 404: `/reps/manifest.json`, `/reps/sw.js`, `/reps/icons/icon-192.png`, and `/reps/icons/icon-512.png` on `https://mange1213.github.io`.
6. Open `https://mange1213.github.io/reps/` in the full Google Chrome app (not a Custom Tab, in-app browser, or downloaded HTML file). Open Chrome's ⋮ menu and choose **Install app** or **Add to Home screen**.

## Included
- `index.html`: sales activity app with representative settings, weekly/monthly formatted Excel exports, CSV export and JSON backup/restore.
- `manifest.json`: PWA metadata and 192/512 standard and maskable icons.
- `sw.js`: offline app-shell cache, versioned `v6` to replace old cached releases.
- `icons/`: app icons.

## Important
The ZIP cannot publish itself to GitHub or force Chrome to install the app. The files must be uploaded to the repository and served over HTTPS. Chrome controls whether its install option is available. If the menu still has no install option, confirm the four resource URLs above and that the exact `/reps/` site is being opened in full Chrome.

Activity data is stored locally in the browser on each device. Export backups regularly; this version does not provide cloud sync or shared logins.
