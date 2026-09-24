MY DAY — GitHub / Offline package

Files:
- index.html: main website/app entry point.
- manifest.webmanifest: PWA metadata for install/standalone mode.
- sw.js: service worker for offline app-shell caching.

For GitHub Pages:
1. Upload all files in this folder to the repository root.
2. Keep index.html at the root.
3. Enable GitHub Pages for the repository.
4. Open the Pages URL once while online; the service worker can then cache the app shell for offline use.

The app stores its user data in the browser's local storage. The main HTML is self-contained; no image/icon asset folder is required.
