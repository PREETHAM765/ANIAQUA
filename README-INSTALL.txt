ANIAQUA — INSTALLATION NOTES

This folder contains the complete Aniaqua web app and installable PWA files.

RUN LOCALLY
1. Extract the ZIP.
2. Open the folder in Replit or another static web host.
3. Serve index.html from a local web server. A PWA cannot be installed from a file:// URL.

INSTALL ON ANDROID
1. Deploy the folder to a public HTTPS address (for example, Replit Deployments).
2. Open that HTTPS address in Chrome on Android.
3. Open Chrome's menu (three dots).
4. Choose "Install app" or "Add to Home screen".
5. Confirm. Aniaqua will appear on your home screen and open in its own app-like window.

IMPORTANT
- This is an installable Progressive Web App (PWA), not a signed Android APK.
- It requires HTTPS for installation and service-worker offline support.
- Your current app stores entries in this browser's LocalStorage. Data does not automatically sync between devices.
- Anime/manga auto-fill uses AniList and requires an internet connection.
- Use Export library regularly to keep a backup of your collection.


ANIAQUA PERSONAL EDITION UPDATE
- Anime and manga live suggestions use the public Jikan API (MyAnimeList data).
- Movie suggestions use Wikipedia search/summary; movie metadata coverage varies.
- No login or backend is required. Your collection stays in this browser.
- Use Export library / Import backup regularly. Clearing browser storage can erase local data.
- Total season count is a manual field because catalogue APIs do not consistently provide a reliable franchise-wide season total. Episode counts are intentionally omitted.
- Installable PWA cache version updated.
