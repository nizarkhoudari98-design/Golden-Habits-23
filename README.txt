GOLDEN HABITS — INSTALL GUIDE

This is an installable Progressive Web App (PWA) for Android, including Samsung Galaxy Z Fold devices.

IMPORTANT: A PWA must be served from an HTTPS website to install as an app. Opening index.html directly from a ZIP will let you preview it on a computer, but will not enable proper Android installation or notifications.

EASIEST PUBLISHING ROUTE (GitHub Pages — free):
1. On a computer, open https://github.com and create a free account/sign in.
2. Create a new repository named golden-habits. Set it to Public. Create repository.
3. Choose Add file > Upload files. Upload the CONTENTS of this folder (index.html, manifest.json, sw.js, icons folder). Commit the files.
4. In the repository, open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch. Select main and /(root), then Save.
6. Wait a minute or two. GitHub will show your site address, usually https://YOUR-USERNAME.github.io/golden-habits/ .
7. On your Z Fold, open that address in Chrome. Tap ⋮ > Install app (or Add to Home screen > Install). Open Golden Habits from your app drawer.
8. Tap Enable reminders and allow notifications. In Reminders, set your daily check-in time.

HOW IT WORKS:
- Daily, monthly and yearly habits; add and delete your own habits.
- Tick a habit when completed. A supportive message appears.
- Progress ring and daily completion count.
- Habits and settings are stored locally in the browser on this device.
- The app shell works offline after its first successful load.

NOTIFICATION LIMITATION:
This starter version uses browser notifications and checks reminder times while the app is open or active in the background. Android may pause browser timers when the app is fully closed or the phone is in deep sleep. It does NOT promise alarm-clock reliability when fully closed. Reliable scheduled notifications at any time require a push-notification service/backend or a native Android app.

DATA:
Your habit data is saved in local browser storage. Clearing Chrome site data or uninstalling/clearing the app may erase it. There is no cloud sync in this version.
