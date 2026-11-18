FOOTBALL MATCH ANALYST V2 — INSTALLATION

CONTENTS
- index.html: the app
- manifest.json: installable app settings
- sw.js: offline cache
- README.txt: these instructions

IMPORTANT
This is an installable Progressive Web App (PWA), not an Android APK.
It does not connect to 1Win and does not automatically retrieve live fixtures,
injuries, team form or bookmaker odds. Enter verified data manually.
Its comparison score is a rough indicator, NOT a true probability or guarantee.

INSTALL ON ANDROID
1. Upload all three app files (index.html, manifest.json, sw.js) to the same folder
   on an HTTPS static website. GitHub Pages is one option.
2. Open the HTTPS address in Google Chrome on your Android phone.
3. Open Chrome's three-dot menu and choose "Install app" or "Add to Home screen".
4. Open the installed app. It can then work offline after the first successful load.

FEATURES
- Team form points from last five results (W/D/L)
- Goals scored and conceded comparison
- Optional head-to-head comparison and injury notes
- Optional 1-X-2 odds and implied market percentages
- Save analyses locally on the phone
- Export/import JSON backup
- Add saved matches to an accumulator
- Calculate combined odds, potential return and profit for a stake

DATA NOTE
Saved analyses are stored in the browser on that device. Clearing browser/site data
may erase them, so export a backup periodically.
