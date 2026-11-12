# Lift Log: how to put it on your phone

This folder is the whole app. Put it on a free website once, then install it from your phone. After that it works offline, with no internet needed at the gym.

## 1. Put it online (free, about 10 minutes, easiest on a computer)

### Option A: GitHub Pages (recommended, stays up forever)

1. Make a free account at github.com.
2. Click **+** (top right), then **New repository**. Name it `liftlog`, set it to **Public**, and click **Create repository**.
3. On the next page, click **uploading an existing file**.
4. Unzip `liftlog-app.zip`. Drag everything inside the `liftlog` folder (`index.html`, `manifest.webmanifest`, `sw.js` and the `icons` folder) into the upload box. Click **Commit changes**.
5. Go to the repository's **Settings**, then **Pages** in the left menu. Under "Branch", pick **main** and **/ (root)**, then click **Save**.
6. Wait 1–2 minutes and refresh. Your app's address appears at the top, like `https://YOUR-USERNAME.github.io/liftlog/`.

### Option B: Netlify Drop (fastest)

1. Go to app.netlify.com/drop.
2. Drag the unzipped `liftlog` folder onto the page.
3. Make a free account when it asks, so the site isn't deleted. You get an address like `https://something.netlify.app`.

## 2. Install it on your phone

**iPhone:** open your app's address in **Safari**, tap **Share** (the square with the arrow), then **Add to Home Screen**.

**Android:** open the address in **Chrome**, tap the three dots, then **Install app** or **Add to Home screen**.

Open it once from the new icon while you have internet. After that it works offline.

## Important: where your logs are saved

- Your logs are saved **inside the installed app on your phone**, not online.
- **On iPhone, always log from the home-screen icon**, not from Safari. They keep separate storage, so logs typed in Safari won't show up in the app.
- Deleting the app or clearing website data **deletes your logs**. Use **Plan → Save backup** every couple of weeks and before changing phones, and keep the file in iCloud Drive, Google Drive or email.
- On a new phone, install the app, then use **Plan → Restore from file**.

## Updating the app later

If I send you a new `index.html`, upload it to the same place, replacing the old one. Also open `sw.js` and change `liftlog-v1` to `liftlog-v2` (then v3, and so on), so phones pick up the new version. Your logs are kept.
