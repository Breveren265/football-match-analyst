BREVEREN ANALYSIS APP — VERSION 3

WHAT IT DOES
- Retrieves upcoming fixtures automatically from API-Football.
- Lets you choose a date range and optionally filter by league.
- Requests the provider's match prediction for each selected fixture.
- Displays the provider's home/draw/away percentages and advice.
- Installs as a Progressive Web App (PWA) through GitHub Pages.

IMPORTANT DATA REQUIREMENT
This app requires an API-Football API key. Register at:
https://dashboard.api-football.com/register
The provider currently advertises a free tier with 100 requests per day. Limits,
coverage, availability and endpoint permissions can change. The app does not
include a key and does not bypass provider limits.

HOW TO INSTALL
1. Extract this ZIP.
2. Upload index.html, manifest.json, sw.js, icon.svg and README.txt to the ROOT
   of the existing public GitHub repository (football-match-analyst).
3. Commit the changes.
4. Keep GitHub Pages set to Deploy from a branch / main / /(root).
5. Open https://breveren265.github.io/football-match-analyst/ in Chrome.
6. Use Chrome menu > Install app / Add to Home screen.

FIRST USE
1. Register for an API-Football key.
2. Paste the key into the app and tap "Save key on this phone".
3. Select dates and tap "Load fixtures automatically".
4. Tap "Analyse this match" or "Analyse first 10 fixtures".

PRIVACY
The API key is stored in local browser storage on the device. Anyone with access
to the browser/device may be able to use it. Do not publish the key in GitHub,
screenshots, messages or source files. Clear browser site data to remove it.

LIMITATIONS
- Requires internet access and a valid API key.
- Fixture and prediction coverage depends on API-Football and your plan.
- Automatic analysis is based on provider prediction data, not a guarantee.
- It does not place bets, connect to 1Win, or guarantee profits.
- The free API quota can be consumed quickly when analysing many matches.
