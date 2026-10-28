# R.N & CO Technical Studio

Estimates, technical calculators, unit converter and drawing studio for R.N & CO.
Runs in the browser, works offline once opened, and can be installed as an app.

## Files
- index.html - the app
- manifest.webmanifest - app name, colours and icons
- sw.js - service worker (offline support)
- icons/ - app icons
- .nojekyll - tells GitHub Pages to serve files as-is

## Publish on GitHub Pages
1. Create a new repository on GitHub (e.g. rn-co-estimator). Make it Public.
2. Upload ALL files and the icons folder (unzip the zip first; GitHub does not unzip for you).
3. Go to Settings > Pages. Under "Build and deployment" choose Deploy from a branch, branch main, folder / (root). Save.
4. After about a minute your site is live at:
   https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/

## Make it an app with PWA Builder
1. Open https://www.pwabuilder.com and paste the GitHub Pages link above.
2. Review the report, then choose Package for stores (Android, Windows, etc.).
3. Download the package and follow PWA Builder's instructions for each store.

Note: all data is saved on the device (browser storage). Clearing browser data erases saved estimates.
