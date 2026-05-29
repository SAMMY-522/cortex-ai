# CORTEX — Your Second Brain PWA

Save reels, notes & links. Ask AI. Works from Android share sheet.

## Deploy to GitHub Pages (free, 5 mins)

1. Go to https://github.com and create a free account (if you don't have one)
2. Click **New repository** → name it `cortex` → set to **Public** → Create
3. Click **"uploading an existing file"** → drag all 4 files (index.html, manifest.json, sw.js, icon.svg)
4. Click **Commit changes**
5. Go to repo **Settings → Pages → Source → Deploy from branch → main → / (root) → Save**
6. Wait 1 minute → your app is live at: `https://YOUR_USERNAME.github.io/cortex`

## Setup on Android

1. Open the GitHub Pages URL in **Chrome**
2. Chrome will show **"Add to Home Screen"** banner — tap it
3. CORTEX is now installed as an app on your phone

## Enable Share Sheet (so you can share reels directly to CORTEX)

After installing on home screen:
- Open any Instagram/YouTube reel
- Tap **Share → More** → look for **CORTEX** in the list
- Tap CORTEX → it opens with the URL pre-filled → add your notes → Save

## API Key Setup

1. Go to https://console.anthropic.com
2. Create an account → go to API Keys → Create Key
3. In CORTEX → tap **Setup** tab → paste your key → Save
4. Now Ask AI works with all your saved content

## Files
- `index.html` — full app
- `manifest.json` — PWA config + share target
- `sw.js` — service worker (offline support)
- `icon.svg` — app icon
