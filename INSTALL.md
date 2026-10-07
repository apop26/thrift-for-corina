# Thrift for Corina: hosting and installing

Hosting: any static host works. GitHub Pages: put index.html, sw.js, manifest.webmanifest and the icons/ and fonts/ folders at the top level of the repo, then Settings > Pages > deploy from the main branch.

Install on an iPhone (has to be Safari)
1. Open the https link in Safari.
2. Tap the Share button, then Add to Home Screen, then Add.
3. Open it once with signal so it saves itself, then once in airplane mode to check it works offline.
4. Tap Find me on a city's Map tab and allow location when asked.

Updating later: ask for a rebuild. The version number shows at the bottom of the app and in sw.js (thrift-for-corina-vN); if you ever edit by hand, change both together so phones pick up the new copy.

Map: Leaflet (BSD licence, LEAFLET-LICENSE.txt) with OpenStreetMap tiles; the streets need internet.

Icon: white handbag on terracotta. The title font (Lobster, SIL Open Font License) is built into index.html; its licence file is in fonts/.
