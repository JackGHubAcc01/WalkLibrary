WALKLIBRARY V0.2
================

WHAT'S NEW
- Real interactive online map using Leaflet + OpenStreetMap.
- Multiple saved walks stored locally on the device.
- Add, edit and delete walks.
- Search and filters.
- Saved / Planned / Completed status.
- GPX import: track points are parsed and stored locally for later display.
- Castle Tioram remains Walk #001.
- App shell, saved walk data and GPX data remain available offline.

IMPORTANT V0.2 LIMITATION
The interactive map BACKGROUND is online-only. Walk details and imported GPX data are retained locally, but V0.2 does not bulk-download OpenStreetMap tiles. That is intentional. A later version will test a properly licensed offline-map package.

UPDATING GITHUB PAGES
1. Open your WalkLibrary GitHub repository.
2. Add file > Upload files.
3. Upload ALL V0.2 files from this folder.
4. GitHub will warn that matching files already exist; replacing them is expected.
5. Commit changes with message: Update to WalkLibrary V0.2
6. Wait for GitHub Pages to redeploy.
7. On iPhone, open the installed WalkLibrary while online. If an old version persists, fully close/reopen; Safari/PWA service-worker updates can take another launch.

GPX
Use Add walk (or Edit) > GPX route > choose a .gpx file from Files on iPhone/PC. V0.2 stores route points in browser local storage, so keep GPX files reasonably sized during this prototype.
