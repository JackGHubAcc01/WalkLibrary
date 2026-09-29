WALK LIBRARY V0.1
=================

Purpose
- Prove the phone/PWA workflow before building the full app.
- Castle Tioram is Walk #001.
- The bundled schematic route and app shell work offline after first successful load.
- GPS test uses the phone/browser geolocation API.

IMPORTANT
Opening index.html directly from a ZIP/file will NOT test PWA offline/install correctly.
A PWA needs to be served over HTTPS (or localhost during desktop development).

QUICK DESKTOP TEST
1. Extract this folder.
2. Open a terminal in the folder.
3. If Python is installed: python -m http.server 8080
4. Browse to http://localhost:8080
5. Load once, then use browser DevTools/offline mode and reload.

IPHONE TEST
Host the folder on any HTTPS static host (for example GitHub Pages/Cloudflare Pages), visit it in Safari, then Share > Add to Home Screen.
Open the Home Screen app once while online. Then enable Airplane Mode, fully close it, reopen it, and confirm Castle Tioram + Route still display.

V0.1 LIMITATION
The displayed map is deliberately a bundled schematic, not a navigational map. This proves offline app storage without violating public map-tile download policies. V0.2 can add GPX import and a real online MapLibre map; after that we can prototype a properly licensed offline map package.
