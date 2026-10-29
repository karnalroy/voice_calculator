VOICE CALCULATOR PWA
====================

Files:
- index.html: calculator app
- manifest.json: installable app metadata
- sw.js: offline cache service worker
- icon.svg, icon-192.png, icon-512.png: app icons

IMPORTANT:
A PWA must be served over HTTPS (or localhost for development). Opening index.html directly as a file will not enable installation or the service worker.

EASIEST PUBLISHING OPTION:
1. Upload the contents of this folder to a static HTTPS host such as GitHub Pages or Netlify.
2. Open the resulting HTTPS site in Chrome on Android or Chrome/Edge on Windows.
3. Android: browser menu > Install app / Add to Home screen.
4. Windows: use the install icon in the browser address bar, or browser menu > Install app.

VOICE NOTES:
- Voice recognition works only in browsers that support the Web Speech API and may require internet access.
- The current build is optimized for English recognition and includes a few simple Hindi command aliases. Full Hindi number-word recognition is not yet complete.
- Standard keypad calculations work offline after the app has been loaded and cached.
