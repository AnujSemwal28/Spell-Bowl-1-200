SPELL BOWL PWA

FILES
- index.html: app
- manifest.webmanifest: installation metadata
- service-worker.js: offline cache
- icons/: install icons

IMPORTANT
A Progressive Web App must be served over HTTPS (or localhost during testing). Opening index.html directly with file:// will run the quiz, but installation and offline caching will not activate.

QUICK HOSTING
Upload every file and folder in this package to the same website root. Do not rename or omit the icons folder. After the HTTPS site loads, use the Install app button when shown, or the browser's install/add-to-home-screen command.

LOCAL TEST
From the unzipped folder, run a local static server such as: python -m http.server 8000
Then open http://localhost:8000 in a browser.
