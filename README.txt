BEAT BUDDY! — FREE INSTALLABLE PWA

FILES
- index.html: app structure
- styles.css: colorful responsive UI
- app.js: sequencer, synthesized sounds, piano, save/load and recording
- manifest.webmanifest: installable app metadata
- sw.js: offline cache / service worker
- icons/: app icons

RUN LOCALLY
For a quick preview, open index.html in a modern browser. Audio and beat editing work; PWA installation and offline caching require HTTPS or localhost.

PUBLISH FREE WITH GITHUB PAGES
1. Create/sign in to a GitHub account.
2. Create a public repository named beat-buddy.
3. Upload the CONTENTS of this folder (index.html, styles.css, app.js, manifest.webmanifest, sw.js, icons/).
4. In repository Settings > Pages, choose Deploy from a branch, select main and /(root), then Save.
5. Wait for the published Pages URL. Open it in Chrome on Android.
6. Use the browser menu > Install app (or Add to Home screen).

NOTES
- PWA installation/service worker requires HTTPS; GitHub Pages supplies HTTPS.
- Saved beats are stored in the browser on that device, not synced to other devices.
- Audio export uses MediaRecorder and saves WebM audio in browsers that support it.
- This is a static app; it does not collect user data or require an account.
- Google Fonts is an optional online font; the app uses system font fallbacks offline.
