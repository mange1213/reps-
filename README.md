# Sales Representative Reports — Installation repair v5

Configured for the GitHub Pages project: https://mange1213.github.io/reps/

## Upload the complete app
1. Extract this ZIP on your phone or computer.
2. Open https://github.com/mange1213/reps and upload/replace the extracted files at the repository root. Keep the `icons` folder and both PNG files. Do not upload only `index.html`.
3. In GitHub, open **Settings → Pages** and verify the branch/folder being published. Wait for the deployment to finish.
4. Check that these URLs load (none should show a 404):
   - https://mange1213.github.io/reps/manifest.json
   - https://mange1213.github.io/reps/sw.js
   - https://mange1213.github.io/reps/icons/icon-192.png
   - https://mange1213.github.io/reps/icons/icon-512.png
5. Open https://mange1213.github.io/reps/ in the full Google Chrome app, not a preview or in-app browser. Tap Chrome **⋮ → Install app** or **Add to Home screen**.

## What this repair changes
- Install buttons stay visible in a normal browser, even if an old version incorrectly saved an “installed” flag.
- The install button invokes Chrome's install prompt when Chrome provides one; otherwise it explains how to install from Chrome's menu.
- The service-worker cache has been versioned to v5 so the new files replace the previous cached shell.
- The manifest uses `/reps/` as the app ID, start URL and scope.

## Important limitation
A ZIP cannot publish itself to GitHub or force Android/Chrome to install an app. The website must be published over HTTPS, and Chrome decides whether to show installation. If Chrome's menu has no install option after deployment, verify the four URLs above and make sure you opened the correct URL in the full Chrome app.

Sales activities are stored locally in that browser on that device. Export Excel/CSV and JSON backups regularly. This version does not provide logins or cloud sync.
