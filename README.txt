ScoreTracker app-style/PWA version

Upload ALL these files to the ROOT of the GitHub repository webhitsdesign/ScoreTracker-:
index.html
manifest.webmanifest
sw.js
icon-192.png
icon-512.png
apple-touch-icon.png

GitHub Pages must be enabled for the main branch root.
Open https://webhitsdesign.github.io/ScoreTracker-/ on your phone.

iPhone: Open in Safari > Share > Add to Home Screen.
Android: Open in Chrome > menu > Add to Home screen or Install app.

The app opens in a standalone window when installed where supported.
The service worker caches app files for offline use after the first online visit.
Game data/history remain in browser storage on that device, not synced across devices.
Offline support requires HTTPS and an initial successful online load.
