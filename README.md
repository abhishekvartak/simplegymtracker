# Gym Tracker

A personal gym, bodyweight and calorie tracker that installs on a phone from the browser.
No account and no server: everything is stored on the device it is used on.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole app: screens, charts, calculations and on-device storage |
| `sw.js` | Lets the app open with no signal |
| `manifest.webmanifest` | App name, icon and full-screen setting for "Add to Home Screen" |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | App icons |

## Put it online with GitHub Pages

1. On github.com, create a new **public** repository, for example `gym-tracker`.
2. Open the repository, choose **Add file > Upload files**, drag in every file from this folder, and commit.
3. Go to **Settings > Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, pick **main** and **/ (root)**, then Save.
4. Wait a minute or two. The page shows the address, in the form `https://YOUR-USERNAME.github.io/gym-tracker/`.

## Install on an iPhone

1. Open that address in **Safari**.
2. Tap **Share**, then **Add to Home Screen**.
3. Open it from the new icon. Tap "Clear demo data and start my own" to begin.

## Updating the app later

Replace the changed files in the repository. If `index.html` or any other file changed,
also raise the version on the first line of `sw.js` (`gym-tracker-v1` to `gym-tracker-v2`)
so installed phones pick up the new version.

## Your data

Data lives only in the app on that phone. Use **Setup > Save a backup file** regularly.
Deleting the home-screen app or clearing Safari website data erases it.
