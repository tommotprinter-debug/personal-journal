# Personal Journal — GitHub Pages PWA

DOS-inspired private journal packaged as an installable Progressive Web App.

## Publish on GitHub Pages

1. Create a new GitHub repository, for example `personal-journal`.
2. Upload **all files and the `icons` folder from this package to the repository root**.
3. Commit the files to your default branch, normally `main`.
4. Open **Settings → Pages** in that repository.
5. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
6. Choose **main** and **/(root)**, then click **Save**.
7. GitHub will publish the app at a URL similar to:
   `https://YOUR-USERNAME.github.io/personal-journal/`

## Install on Android

1. Open the published GitHub Pages address in **Google Chrome**.
2. Tap **⋮**.
3. Choose **Install app** or **Add to Home screen**.
4. Confirm.
5. Open **Journal** from your home screen or app drawer.

## Data and privacy

Journal entries are stored locally in the browser/PWA storage on your device. They are **not committed or uploaded to GitHub**.

Use **BACKUP JOURNAL** regularly. Clearing Chrome site data, uninstalling the app, or moving the app to another web address can make locally stored entries unavailable.

## Updating later

Upload newer app files into the same repository and commit them. GitHub Pages will republish the app. Keeping the same Pages URL is important because local browser storage is associated with that site.


## Built-in Android install button

Version 7 adds **INSTALL JOURNAL** to the DOS landing page.

When Chrome exposes the PWA `beforeinstallprompt` event, the button opens Android's native install dialog. If the browser does not expose that event, the app shows the fallback route: **Chrome menu → Install app / Add to Home screen**.

After successful installation, the landing page changes the button to **JOURNAL INSTALLED** when the app is running in standalone mode.
