Playlist Maker (PWA) - how to put it on GitHub Pages
1. On GitHub, create a new PUBLIC repository named playlist-maker (free Pages needs a public repo).
2. Upload ALL files from this folder to the repo root (index.html, sw.js, manifest.webmanifest, 4 png files).
3. Settings > Pages > Build and deployment: Source "Deploy from a branch", branch main, folder / (root). Save.
4. After a minute the page is at https://<your-username>.github.io/playlist-maker/
5. Open it in Chrome on the phone, menu > Install app (or Add to Home screen).
Updating later: upload the new files over the old ones and raise VERSION in sw.js (pm-1 -> pm-2) so phones refresh.
