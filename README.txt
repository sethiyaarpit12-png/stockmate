# StockMate Pro — Install on Your Phone (Free, Personal Use)

## What's in this folder
```
stockmate/
├── index.html      ← The full app
├── manifest.json   ← Makes it installable like a native app
├── sw.js           ← Makes it work offline
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

---

## Step 1 — Upload to GitHub Pages (Free Hosting)

1. Go to https://github.com and create a free account (if you don't have one)
2. Click the **+** button → **New repository**
3. Name it: `stockmate` (all lowercase)
4. Set to **Public**, click **Create repository**
5. Click **uploading an existing file**
6. Drag and drop ALL files from this folder:
   - index.html
   - manifest.json
   - sw.js
   - icons/icon-192.png  ← make sure to upload into an `icons` folder
   - icons/icon-512.png
7. Click **Commit changes**
8. Go to **Settings** → **Pages** → Source: **Deploy from branch** → Branch: **main** → Save
9. Wait 1-2 minutes → Your app URL will be:
   `https://YOUR-USERNAME.github.io/stockmate/`

---

## Step 2 — Install on Android Phone

1. Open **Chrome** on your Android phone
2. Go to your app URL (e.g. `https://yourname.github.io/stockmate/`)
3. A banner will appear: **"Install StockMate"** → Tap **Install**
4. OR tap the 3-dot menu → **Add to Home Screen**
5. Done! The app icon appears on your home screen like a native app ✅

---

## Step 3 — Install on iPhone

1. Open **Safari** on your iPhone (must be Safari, not Chrome)
2. Go to your app URL
3. Tap the **Share button** (box with arrow pointing up)
4. Scroll down and tap **"Add to Home Screen"**
5. Tap **Add** in the top right
6. Done! App icon appears on your home screen ✅

---

## Features
- ✅ Works 100% offline after first visit
- ✅ All data saved on your phone (localStorage)
- ✅ Looks and feels like a native app (no browser bar)
- ✅ QR code generation for every product
- ✅ Low stock alerts
- ✅ Full stock movement history

---

## Alternative: Netlify (Even Easier)

1. Go to https://netlify.com → Sign up free
2. Drag the entire `stockmate` folder onto the Netlify dashboard
3. Get your URL instantly (e.g. `https://stockmate-abc123.netlify.app`)
4. Follow Step 2 or 3 above to install on phone
