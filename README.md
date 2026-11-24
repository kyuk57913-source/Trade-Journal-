# Trade Journal

A static, mobile-friendly trading journal app prepared for GitHub Pages. No build step or backend is required. Trades are stored in the browser's local storage; use the app's built-in backup/export tools to keep a copy of your data.

## Publish with GitHub Pages

1. Create a GitHub repository (for example, `trade-journal`).
2. Upload **all files and folders in this directory** to the repository root. Keep `index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll`, and the `assets/` folder together.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select your default branch (usually `main`) and folder **`/ (root)`**, then click **Save**.
5. Wait for the Pages deployment to finish. Open the URL shown in the Pages settings.

GitHub Pages can take a minute or two to publish the first deployment. The same relative paths work for both a user site and a project site such as `https://username.github.io/trade-journal/`.

## Install on a phone

Open the published HTTPS URL in the browser and use **Add to Home screen / Install app**. The manifest and 192/512-pixel app icons are included. The service worker caches the app shell for repeat/offline launches. Updates may take a reload after deployment.

## Data and privacy

Trade entries are saved locally in the browser on that device. They are not synced to GitHub or a server. Clearing browser storage can remove them, so export a backup regularly and keep it somewhere safe. Do not put private trade data in the GitHub repository.

## Files

- `index.html` — full app and interface
- `assets/app-icon-192.png`, `assets/app-icon-512.png` — browser and install icons
- `assets/app-icon-master.png` — high-resolution master logo
- `manifest.webmanifest` — installable app metadata
- `sw.js` — offline app-shell cache
- `.nojekyll` — tells GitHub Pages to publish files as-is
