# 📱 How to Install My Personal Hub on Android

Your hub is a **PWA (Progressive Web App)** — it installs like a real app, works offline,
and never needs the Play Store. Follow these 3 steps:

---

## Step 1 — Upload to GitHub Pages (free hosting, 5 minutes)

1. Go to **github.com** and create a free account (if you don't have one)
2. Click **"New repository"** (the green button)
3. Name it: `my-hub` (or anything you like)
4. Make it **Public**
5. Click **"Create repository"**
6. Click **"uploading an existing file"** link on the next screen
7. Drag and drop ALL these files into the upload box:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - The entire `icons/` folder (all 8 PNG files inside it)
8. Click **"Commit changes"**
9. Go to **Settings → Pages** (left sidebar)
10. Under "Source", select **"Deploy from branch"** → branch: `main` → folder: `/ (root)`
11. Click **Save**
12. Wait ~2 minutes. Your URL will appear as:
    `https://YOUR_USERNAME.github.io/my-hub/`

---

## Step 2 — Open in Chrome on Android

1. Open **Google Chrome** on your Android phone
2. Go to your GitHub Pages URL:
   `https://YOUR_USERNAME.github.io/my-hub/`
3. Wait for the page to fully load

---

## Step 3 — Install to Home Screen

**Option A — Automatic banner (recommended)**
- A banner will appear at the bottom saying "Install My Hub"
- Tap **Install** → done! ✅

**Option B — Manual**
- Tap the **⋮ menu** (3 dots) in Chrome
- Tap **"Add to Home screen"**
- Tap **"Add"** in the popup
- Done! ✅

---

## ✅ After Installing

- The app appears on your home screen with its own icon
- Tap it — it opens like a real app (no browser bar!)
- **Works offline** — all your data is saved locally on the phone
- **AI features** (chat + quotes) need internet to work

---

## 🔄 Updating the App

Whenever you want to update the app (e.g. after Claude adds new features):
1. Upload the new `index.html` to GitHub (same steps as above, it will replace the old one)
2. On your phone, open the app and pull down to refresh once
3. The update is live!

---

## 💡 Tips

- Your data is stored locally on each device (phone + laptop are separate)
- For the AI chat to work, you need an internet connection
- Quotes are cached so you see them offline after first load
- The app works on iPhone too (same steps, use Safari instead of Chrome)

---

## 🆓 Cost

**GitHub Pages is completely free** for public repositories.
Your hub URL is permanent as long as your GitHub account exists.
