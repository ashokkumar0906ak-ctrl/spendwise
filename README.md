# Spendwise PWA — Setup Guide

## What's included
- `index.html` — The full app (single file)
- `manifest.json` — Makes it installable as an app
- `sw.js` — Enables offline support
- `icons/` — App icons

---

## Option 1: Install directly on your phone (easiest)

### Android (Chrome)
1. Copy all 4 files + icons folder to any web host, OR use the free method below
2. Open Chrome → go to the app URL
3. Tap the **⋮ menu** → "Add to Home screen"
4. Tap "Add" → app icon appears on your home screen!

### iPhone (Safari)
1. Open Safari → go to the app URL
2. Tap the **Share button** (box with arrow)
3. Scroll down → tap "Add to Home Screen"
4. Tap "Add" → done!

---

## Option 2: Host it for free in 2 minutes (recommended)

### Using Netlify Drop (no account needed)
1. Go to **netlify.com/drop**
2. Drag and drop the entire `SpendwisePWA` folder
3. Netlify gives you a free URL like `https://amazing-app-123.netlify.app`
4. Open that URL on your phone and install it!

### Using GitHub Pages (free, permanent)
1. Create a free account at github.com
2. Create a new repository → upload all files
3. Go to Settings → Pages → select "main" branch → Save
4. Your app is live at `https://yourusername.github.io/repo-name`

---

## Option 3: Run locally on your computer to test

Install Node.js from nodejs.org, then run:
```bash
npx serve SpendwisePWA
```
Open http://localhost:3000 in your browser.

---

## AI Suggestions (Gemini)
1. Go to **aistudio.google.com**
2. Sign in with your Google account
3. Click **"Get API key"** → Create API key (it's FREE)
4. Paste the key in the app's AI tab

---

## Features
- ✅ Works offline after first load
- ✅ Installs like a native app (no app store)
- ✅ Data saved on your device (private)
- ✅ Add & categorise expenses
- ✅ Set monthly budgets with alerts
- ✅ Savings goals tracker
- ✅ AI spending suggestions (Gemini)
- ✅ 6-month spending trend chart
- ✅ Export your data as JSON
