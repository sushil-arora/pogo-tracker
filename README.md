# POGO Tracker v1.1 — PWA Setup Guide

## Files in this folder
```
index.html      ← The full app (open this in any browser)
manifest.json   ← Makes it installable as an app
sw.js           ← Service worker (offline support)
icon-192.png    ← App icon (home screen)
icon-512.png    ← App icon (splash screen)
```

---

## Step-by-step: Deploy to GitHub Pages

### Step 1 — Create a GitHub account
Go to https://github.com and sign up (free).

### Step 2 — Create a new repository
1. Click the **+** button (top right) → **New repository**
2. Name it: `pogo-tracker`
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload the files
1. On your new repo page, click **uploading an existing file**
2. Drag ALL 5 files into the upload area:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repo → **Settings** tab
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Branch: **main** / folder: **/ (root)**
5. Click **Save**

### Step 5 — Get your URL
After ~1 minute, your app will be live at:
```
https://YOUR-USERNAME.github.io/pogo-tracker/
```

---

## Step-by-step: Install as Android App

1. Open Chrome on your Android phone
2. Go to your GitHub Pages URL above
3. Tap the **⋮ menu** (three dots, top right)
4. Tap **"Add to Home screen"**
5. Tap **"Add"** to confirm
6. The app icon appears on your home screen!

It will open fullscreen like a real app, with no browser UI.

---

## Notes
- Your data is saved locally on your device (localStorage)
- The app works offline after the first load
- The AI screenshot import requires an internet connection
- No account or login needed
